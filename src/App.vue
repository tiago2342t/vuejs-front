<template>
  <div id="app">
    <HeaderNav/>
    <main class="container-fluid">
      <HeroSection/>
    </main>
  </div>
</template>

<script>
import HeaderNav from './components/HeaderNav.vue'
import HeroSection from './components/HeroSection.vue'

export default {
  name: 'App',
  components: {
    HeaderNav,
    HeroSection
  }
}
</script>

<style scoped>
#app {
  background-color: #fefcfb;
}
</style>
