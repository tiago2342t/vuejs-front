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

// export default {
//   name: 'App',
//   components: {
//     HeaderNav,
//     HeroSection,
//   }
// }
</script>

<style>
#app {
  background-color: #fefcfb;
}
</style>
