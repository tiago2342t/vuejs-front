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

<style scoped></style>