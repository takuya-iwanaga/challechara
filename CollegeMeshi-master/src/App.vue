<template>
  <v-app id="app">
    <VHeader />
    <v-main id="main">
      <router-view />
    </v-main>
    <VFooter />
  </v-app>
</template>

<script>
import VHeader from './components/VHeader.vue'
import VFooter from './components/VFooter.vue'
export default {
  components: {
    VHeader,
    VFooter
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c503f;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

#main {
  /* background: url("assets/XXXXX.png"); */
  background-size: cover;
  background-position: center;
  width: auto;
  height: auto;
}
</style>
