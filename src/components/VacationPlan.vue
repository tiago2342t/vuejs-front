<template>
    <section id="tour">
        <div class="container col-xxl-8" id="vacation-plan">
            <div class="row align-items-center justify-content-center">
                <h3 class="centered-title">Best <b class="resaltar">vacation plan</b></h3>
                <p class="prf">Plan your perfect vacation with our travel agency. Choose among hundreds of all-inclusive offers!</p>
            </div>

            <div class="flechas d-flex gap-2 pt-3 pb-4 justify-content-end d-sm-none">
                <button class="btn slider-btn" type="button" data-bs-target="#plans-carousel" data-bs-slide="prev">
                    <i class="bi bi-arrow-left"></i>
                </button>

                <button class="btn slider-btn" type="button" data-bs-target="#plans-carousel" data-bs-slide="next">
                    <i class="bi bi-arrow-right"></i>
                </button>
            </div>

            <div class="container d-flex justify-content-center">
                <div id="plans-carousel" class="carousel carousel-dark slide d-none d-lg-block my-4" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <div class="card-wrapper container-sm d-flex justify-content-around">
                                
                                <div class="card vacation-card mx-2" v-for="plan in plans.slice(8, 11)" :key="plan.id">
                                    <img :src="getDestinationFromPlan(plan.destination).image" class="card-img-top img-fluid rounded" :alt="getDestinationFromPlan(plan.destination).name"/>
                                    <div class="card-body">
                                        <div class="d-flex flex-column flex-sm-row justify-content-between">
                                            <h5 class="card-title">{{ getDestinationFromPlan(plan.destination).name }}</h5>
                                            <h5 class="card-title plan-price">${{ plan.price }}</h5>
                                        </div>
                                        <div class="d-flex flex-column flex-sm-row justify-content-between">
                                            <p class="card-text">
                                                <img src="../assets/img/Navigation.svg" alt="Pointer"/>
                                                {{ plan.trip_days }} days trip
                                            </p>
                                            <p class="px-2 text-body-secondary">
                                                <img src="../assets/img/star_1.png" alt="Rank"/>
                                                {{ getRating(plan.id) }}
                                            </p>
                                        </div>
                                    </div>
                                </div>
                                
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Carrusel para pantallas pequeñas -->
            <VacationPlanSmall/>
        </div>
    </section>
</template>

<script setup>
    import VacationPlanSmall from './VacationPlanSmall.vue';
</script>

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

<style scoped>
#vacation-plan {
    padding: 15vh 0;
}

#vacation-plan .plan-price {
    color: #fa7436;
}

#vacation-plan .card-body {
    margin: 0.1rem;
}
</style>