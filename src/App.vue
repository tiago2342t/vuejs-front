<template>
  <div id="app">
    <HeaderNav/>
    <main class="container-fluid">
      <HeroSection/>
      <ListDo/>
      <DealsDiscounts/>
      <VacationPlan/>
    </main>
  </div>
</template>

<script setup>
import HeaderNav from './components/HeaderNav.vue';
import HeroSection from './components/HeroSection.vue';
import ListDo from './components/ListDo.vue';
import DealsDiscounts from './components/DealsDiscounts.vue';
import VacationPlan from './components/VacationPlan.vue';

// export default {
//   name: 'App',
//   components: {
//     HeaderNav,
//     HeroSection,
//   }
// }
</script>

<style scoped>
#app {
  background-color: #fefcfb;
}
</style>
