<template>
  <TheHeader/>
</template>

<script>
import TheHeader from './components/Header.vue'
export default {
  name: 'App',
  components: {
    TheHeader
  }
}
</script>

<style>
*{
  margin: 0;
}
a{
  text-decoration: none;
}
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
  color: black;
  margin: 0;
}
</style>
