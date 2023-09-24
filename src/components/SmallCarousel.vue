<template>
    <div id="discounts-carousel-sm" class="carousel slide d-lg-none">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <div class="card-wrapper container-sm d-flex justify-content-around">
                    <div class="card discounts-carousel-card">
                        <img src="../assets/img/madrid1.png" class="card-img-top rounded carousel-img" alt="Madrid"/>
                        <div class="card-body">
                            <div class="d-flex align-content-center justify-content-end">
                                <h5 class="card-title col">Madrid</h5>
                                <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                <p class="mx-2 d-flex justify-content-end">4.8</p>
                            </div>
                            <div class="d-flex align-content-center justify-content-end">
                                <i class="bi bi-geo-alt-fill locate-img"></i>
                                <p class="card-text col">Spain</p>
                                <p class="card-text tachado mx-3">$950</p>
                                <b class="card-text precio h-50 w-25 d-flex justify-content-center">$850</b>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="carousel-item">
                <div class="card-wrapper container-sm d-flex justify-content-around">
                    <div class="card discounts-carousel-card">
                        <img src="../assets/img/firenze1.png" class="card-img-top rounded carousel-img" alt="Firenze"/>
                        <div class="card-body">
                            <div class="d-flex align-content-center justify-content-end">
                                <h5 class="card-title col">Firenze</h5>
                                <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                <p class="mx-2 d-flex justify-content-end">4.5</p>
                            </div>
                            <div class="d-flex align-content-center justify-content-end">
                                <i class="bi bi-geo-alt-fill locate-img"></i>
                                <p class="card-text col">Italy</p>
                                <p class="card-text tachado mx-3">$850</p>
                                <b class="card-text precio h-50 w-25 d-flex justify-content-center">$750</b>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="carousel-item">
                <div class="card-wrapper container-sm d-flex justify-content-around">
                    <div class="card discounts-carousel-card">
                        <img src="../assets/img/paris1.png" class="card-img-top rounded carousel-img" alt="Paris"/>
                        <div class="card-body">
                            <div class="d-flex align-content-center justify-content-end">
                                <h5 class="card-title col">Paris</h5>
                                <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                <p class="mx-2 d-flex justify-content-end">4.4</p>
                            </div>
                            <div class="d-flex align-content-center justify-content-end">
                                <i class="bi bi-geo-alt-fill locate-img"></i>
                                <p class="card-text col">France</p>
                                <p class="card-text tachado mx-3">$699</p>
                                <b class="card-text precio h-50 w-25 d-flex justify-content-center">$599</b>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="carousel-item">
                <div class="card-wrapper container-sm d-flex justify-content-around">
                    <div class="card discounts-carousel-card">
                        <img src="../assets/img/london1.png" class="card-img-top rounded carousel-img" alt="London"/>
                        <div class="card-body">
                            <div class="d-flex align-content-center justify-content-end">
                                <h5 class="card-title col">London</h5>
                                <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                <p class="mx-2 d-flex justify-content-end">4.8</p>
                            </div>
                            <div class="d-flex align-content-center justify-content-end">
                                <i class="bi bi-geo-alt-fill locate-img"></i>
                                <p class="card-text col">UK</p>
                                <p class="card-text tachado mx-3">$950</p>
                                <b class="card-text precio h-50 w-25 d-flex justify-content-center">$850</b>
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

            <button class="btn slider-btn mx-2 my-3" type="button" data-bs-target="#discounts-carousel-sm" data-bs-slide="next">
                <i class="bi bi-arrow-right"></i>
            </button>
        </div>
    </div>
</template>

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