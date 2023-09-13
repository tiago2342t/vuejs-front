<template>
  <div id="app">
    <HeaderNav/>
    <main class="container-fluid">
      <HeroSection/>
      <ListDo/>
    </main>
  </div>
</template>

<script setup>
import HeaderNav from './components/HeaderNav.vue'
import HeroSection from './components/HeroSection.vue'
import ListDo from './components/ListDo.vue';

// export default {
//   name: 'App',
//   components: {
//     HeaderNav,
//     HeroSection
//   }
// }
</script>

<style scoped>
#app {
  background-color: #fefcfb;
}
</style>
