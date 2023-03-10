<template>
  <TheHeader ref1="Как продать квартиру"
             ref2="Истории клиентов"
             number="+7 495 835 47 11"/>
  <TheBlock1/>
  <TheBlock2/>
  <TheBlock3/>
  <TheFooter/>
</template>

<script>
import TheHeader from './components/Header.vue'
import TheBlock1 from './components/Block1.vue'
import TheBlock2 from './components/Block2.vue'
import TheBlock3 from './components/Block3.vue'
import TheFooter from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    TheHeader,
    TheBlock1,
    TheBlock2,
    TheBlock3,
    TheFooter
  }
}
</script>

<style>
*{
  margin: 0;
}
a{
  text-decoration: none;
  transition: 0.2s;
}
a:hover{
  color: #D44B4B;
}
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
  color: black;
  margin: 0;
}
</style>
