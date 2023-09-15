<template>
    <section id="tour">
        <div class="container col-xxl-8" id="vacation-plan">
            <div class="row align-items-center justify-content-center">
                <h3 class="centered-title">Best <b class="resaltar">vacation plan</b></h3>
                <p class="prf">Plan your perfect vacation with our travel agency. Choose among hundreds of all-inclusive offers!</p>
            </div>
            <div class="flechas d-flex gap-2 pt-3 pb-4 justify-content-end">
                <button class="btn" href="#">
                    <i class="bi bi-arrow-left"></i>
                </button>

                <button class="btn" href="#">
                    <i class="bi bi-arrow-right"></i>
                </button>
            </div>
            <div class="row row-cols-1 row-cols-md-3 g-4 align-items-center justify-content-center">
                <div class="col col-sm-6 col-md-5 col-lg-4">
                    <div class="card w-100 h-100">
                        <img src="../assets/img/rome1.png" class="card-img-top img-fluid rounded" alt="Rome, Italy"/>
                        <div class="card-body">
                            <div class="d-flex flex-column flex-sm-row justify-content-between">
                                <h5 class="card-title">Rome, Italy</h5>
                                <h5 class="card-title plan-price">$5,42k</h5>
                            </div>
                            <div class="d-flex flex-column flex-sm-row justify-content-between">
                                <p class="card-text">
                                    <img src="../assets/img/Navigation.svg" alt="Pointer"/>
                                    10 days trip
                                </p>
                                <p class="px-2 text-body-secondary">
                                    <img src="../assets/img/star_1.png" alt="Rank"/>
                                    4.8
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col col-sm-6 col-md-5 col-lg-4">
                    <div class="card w-100 h-100">
                        <img src="../assets/img/london21.png" class="card-img-top img-fluid rounded" alt="London, United Kingdom"/>
                        <div class="card-body">
                            <div class="d-flex flex-column flex-sm-row justify-content-between">
                                <h5 class="card-title">London, UK</h5>
                                <h5 class="card-title plan-price">$2,42k</h5>
                            </div>
                            <div class="d-flex flex-column flex-sm-row justify-content-between">
                                <p class="card-text">
                                    <img src="../assets/img/Navigation.svg" alt="Pointer"/>
                                    7 days trip
                                </p>
                                <p class="px-2 text-body-secondary">
                                    <img src="../assets/img/star_1.png" alt="Rank"/>
                                    4.7
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col col-sm-6 col-md-5 col-lg-4">
                    <div class="card w-100 h-100">
                        <img src="../assets/img/osaka1.png" class="card-img-top img-fluid rounded" alt="Osaka, Japan"/>
                        <div class="card-body">
                            <div class="d-flex flex-column flex-sm-row justify-content-between">
                                <h5 class="card-title">Osaka, Japan</h5>
                                <h5 class="card-title plan-price">$5,42k</h5>
                            </div>
                            <div class="d-flex flex-column flex-sm-row justify-content-between">
                                <p class="card-text">
                                    <img src="../assets/img/Navigation.svg" alt="Pointer"/>
                                    10 days trip
                                </p>
                                <p class="px-2 text-body-secondary">
                                    <img src="../assets/img/star_1.png" alt="Rank"/>
                                    4.8
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup></script>

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

.centered-title {
    font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
    font-weight: bold;
    color: #222;
    font-size: 6vh;
    text-align: center;
}

.resaltar {
    color: #fa7436;
}

p {
    color: #666;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

.prf {
    text-align: center;
    font-size: 2.5vh;
}

.card-title {
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    font-weight: bold;
}

.flechas button {
    background: white;
    border: 1px solid #666;
    border-radius: 50%;
}

.flechas button i {
    color: #666;
    font-size: 1.5rem;
}

.flechas button:hover {
    background: #fa7436;
    border: none;
}

.flechas button:hover i {
    color: white;
}

.flechas button:active {
    background-color: white;
    border: none;
}

.flechas button:active i {
    color: #fa7436;
}
</style>