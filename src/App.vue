<template>
  <div id="app">
    <HeaderNav/>
    <main class="container-fluid">
      <HeroSection/>
      <ListDo/>
      <DealsDiscounts/>
      <VacationPlan/>
      <AboutUs/>
      <OurBlog/>
      <SuscriptionForm/>
    </main>
    <TheFooter/>
  </div>
</template>

<script setup>
import HeaderNav from './components/HeaderNav.vue';
import HeroSection from './components/HeroSection.vue';
import ListDo from './components/ListDo.vue';
import DealsDiscounts from './components/DealsDiscounts.vue';
import VacationPlan from './components/VacationPlan.vue';
import AboutUs from './components/AboutUs.vue';
import OurBlog from './components/OurBlog.vue';
import SuscriptionForm from './components/SuscriptionForm.vue';
import TheFooter from './components/TheFooter.vue';
</script>

<style>
#app {
  background-color: #fefcfb;
}

h1, .centered-title {
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
}

h1, .card-title, .centered-title {
  font-weight: bold;
  color: #222;
}

.centered-title {
  font-size: 6vh;
  text-align: center;
}

.card-title {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.resaltar {
  color: #fa7436;
}

p {
  color: #666;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

.card-body {
  padding: 3vh;
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
