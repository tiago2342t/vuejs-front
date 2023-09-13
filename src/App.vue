<template>
  <div id="app">
    <HeaderNav/>
  </div>
</template>

<script>
import HeaderNav from './components/HeaderNav.vue'

export default {
  name: 'App',
  components: {
    HeaderNav
  }
}
</script>

<style scoped>
#app {
  background-color: #fefcfb;
}

h1, h2, h3, h4, h5, h6, .centered-title {
    font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
    font-weight: bold;
    color: #222;
}

.centered-title {
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

footer h5,
.card-title {
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    font-weight: bold;
}

#to-do,
#vacation-plan {
    padding: 15vh 0;
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
