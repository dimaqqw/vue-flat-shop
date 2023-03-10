<template>
  <TheHeader/>
  <TheBlock1/>
  <TheBlock2/>
  <TheFooter/>
</template>

<script>
import TheHeader from './components/Header.vue'
import TheBlock1 from './components/Block1.vue'
import TheFooter from './components/Footer.vue'
import TheBlock2 from './components/Block2.vue'
export default {
  name: 'App',
  components: {
    TheHeader,
    TheFooter,
    TheBlock1,
    TheBlock2
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
