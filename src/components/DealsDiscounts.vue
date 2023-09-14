<template>
    <section id="destination">
        <div class="container col-xxl-8">
            <div class="fila row">
                <h3 class="centered-title">Exclusive <b class="resaltar">deals & discounts</b></h3>
                <p class="prf">
                    Discover our fantastic early booking discounts
                    <br />
                    & start planning your journey.
                </p>
            </div>

            <!-- Carrusel para pantallas grandes -->
            <LargeCarousel/>

            <!-- Carrusel para pantallas pequeñas -->
            <SmallCarousel/>
        </div>
    </section>
</template>

<script setup>
import LargeCarousel from './LargeCarousel.vue';
import SmallCarousel from './SmallCarousel.vue';
</script>

<style scoped>
.centered-title {
    font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
    font-size: 6vh;
    text-align: center;
    font-weight: bold;
    color: #222;
}

.resaltar {
    color: #fa7436;
}

.prf {
    color: #666;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    text-align: center;
    font-size: 2.5vh;
}

.fila {
    padding: 2.5rem 0 5rem;
}
</style>