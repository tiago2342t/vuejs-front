<template>
    <div id="discounts-carousel-sm" class="carousel slide d-lg-none">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <div class="card-wrapper container-sm d-flex justify-content-around">
                    
                    <div class="card discounts-carousel-card" v-for="plan in plans.slice(0, 2)" :key="plan.id">
                        <img :src="getDestinationFromPlan(plan.destination).image" class="card-img-top rounded carousel-img" :alt="getDestinationFromPlan(plan.destination).name"/>
                        <div class="card-body">
                            <div class="d-flex align-content-center justify-content-end">
                                <h5 class="card-title col">{{ getDestinationFromPlan(plan.destination).name }}</h5>
                                <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                <p class="mx-2 d-flex justify-content-end">{{ getRating(plan.id) }}</p>
                            </div>
                            <div class="d-flex align-content-center justify-content-end">
                                <i class="bi bi-geo-alt-fill locate-img"></i>
                                <p class="card-text col">{{ getCountryFromDestination(plan.destination).name }}</p>
                                <p class="card-text tachado mx-3">${{ plan.previous_price }}</p>
                                <b class="card-text precio h-50 w-25 d-flex justify-content-center">${{ plan.price }}</b>
                            </div>
                        </div>
                    </div>
                    
                </div>
            </div>
            <div class="carousel-item">
                <div class="card-wrapper container-sm d-flex justify-content-around">
                    
                    <div class="card discounts-carousel-card" v-for="plan in plans.slice(2, 4)" :key="plan.id">
                        <img :src="getDestinationFromPlan(plan.destination).image" class="card-img-top rounded carousel-img" :alt="getDestinationFromPlan(plan.destination).name"/>
                        <div class="card-body">
                            <div class="d-flex align-content-center justify-content-end">
                                <h5 class="card-title col">{{ getDestinationFromPlan(plan.destination).name }}</h5>
                                <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                <p class="mx-2 d-flex justify-content-end">{{ getRating(plan.id) }}</p>
                            </div>
                            <div class="d-flex align-content-center justify-content-end">
                                <i class="bi bi-geo-alt-fill locate-img"></i>
                                <p class="card-text col">{{ getCountryFromDestination(plan.destination).name }}</p>
                                <p class="card-text tachado mx-3">${{ plan.previous_price }}</p>
                                <b class="card-text precio h-50 w-25 d-flex justify-content-center">${{ plan.price }}</b>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>

        <div class="flechas d-flex justify-content-center">
            <button class="btn slider-btn mx-3 my-3" type="button" data-bs-target="#discounts-carousel-sm" data-bs-slide="prev">
                <i class="bi bi-arrow-left"></i>
            </button>

            <button class="btn slider-btn mx-2 my-3" type="button" data-bs-target="#discounts-carousel" data-bs-slide="next">
                <i class="bi bi-arrow-right"></i>
            </button>
        </div>
    </div>
</template>

<script>
import axios from 'axios';
const plansUrl = 'http://localhost:8000/api/v1/plans/?format=json'
const destinationsUrl = 'http://localhost:8000/api/v1/destinations/?format=json';
const countriesUrl = 'http://localhost:8000/api/v1/countries/?format=json';
const reviewsUrl = 'http://localhost:8000/api/v1/reviews/?format=json';

export default {
    data() {
        return {
            plans: [],
            destinations: [],
            countries: [],
            reviews: []
        }
    },
    mounted() {
        this.getPlansFromAPI();
        this.getDestinationsFromAPI();
        this.getCountriesFromAPI();
        this.getReviewsFromAPI();
    },
    methods: {
        getPlansFromAPI() {
            axios.get(plansUrl)
                .then( response => {
                    this.plans = response.data;
                } )
                .catch( e => console.log('Error getting plans from API: ', e));
        },

        getDestinationsFromAPI() {
            axios.get(destinationsUrl)
                .then( response => {
                    this.destinations = response.data;
                } )
                .catch( e => console.log('Error getting destinations from API: ', e));
        },

        getCountriesFromAPI() {
            axios.get(countriesUrl)
                .then( response => {
                    this.countries = response.data;
                } )
                .catch( e => console.log('Error getting countries from API: ', e));
        },

        getReviewsFromAPI() {
            axios.get(reviewsUrl)
                .then( response => {
                    this.reviews = response.data;
                } )
                .catch( e => console.log('Error getting reviews from API: ', e));
        },

        getDestinationFromPlan(desinationId) {
            return this.destinations[desinationId-1];
        },

        getCountryFromDestination(destinationId) {
            return this.countries[ this.getDestinationFromPlan(destinationId).country-1 ];
        },

        getRating(planId) {
            const planReviews = this.reviews.filter(review => review.plan === planId);

            if(planReviews.length === 0) return 0.0;

            const averageRating = this.calculateAverage(planReviews);
            return averageRating;
        },

        calculateAverage(reviews) {
            const n = reviews.length;
            let sum = 0;
            
            for(let review of reviews) {
                sum += review.rating;
            }

            return sum/n;
        }

    }
}

</script>

<script setup></script>

<style scoped>
.discounts-carousel-card {
    height: auto;
    border-radius: 8px;
    border: 2px solid rgba(102, 102, 102, 0.08);
    background: #fefcfb;
    margin-right: 1rem;
    margin-left: 1rem;
}

.discounts-carousel-card:hover {
    box-shadow: 0px 16px 80px 0px rgba(254, 147, 94, 0.2);
}

.carousel-img:hover {
    filter: brightness(50%);
}

.card-title {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-weight: bold;
    color: #222;
}

.locate-img {
    color: #999;
    height: .25rem;
    margin-right: 2px;
}

.tachado {
    text-decoration: line-through 2px;
    color: #999;
}

.precio {
    background-color: #ffe7db;
    color: #fa7436;
    border-radius: 8px;
}

.slider-btn {
    border: none;
}
</style>