<template>
    <section id="hero-section">
        <div class="container col-xxl-8">
            <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
                <div class="col-10 col-sm-8 col-lg-6">
                    <img src="../assets/img/viajero.png" class="d-block mx-lg-auto img-fluid" alt="Viajero con maleta" width="700" height="500" loading="lazy"/>
                </div>
                <div class="col-lg-6">
                    <h1 class="display-5 fw-bold lh-1 mb-3" id="hero-title">
                        Get started your exciting <b class="resaltar">journey</b> with us.
                    </h1>
                    <p class="lead">
                        A Team of experienced tourism professionals will
                        provide you with the best advice and tips for
                        your desire place.
                    </p>
                    <div class="d-grid gap-2 d-md-flex justify-content-md-start mt-5">
                        <button type="button" class="btn btn-primary btn-lg px-4 me-md-2" id="boton-hero">
                            Discover Now
                        </button>
                    </div>
                </div>
            </div>
        </div>
        <HeroCard/>
    </section>
</template>

<script setup>
import HeroCard from './HeroCard.vue';
</script>

<style scoped>
#hero-section {
    padding: 0 0 15vh 0;
}

#hero-title {
    font-size: 8vh;
}

#boton-hero {
    background-color: transparent;
    color: #fa7436;
    border: 1px solid #fa7436;
    border-radius: 5px;
}

#boton-hero:hover {
    background-color: #fa7436;
    color: white;
}
</style>