<template>
  <TheHeader msg="ТЕСТ"/>
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
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
  text-align: center;
  color: black;
  margin: 0;
}
</style>
