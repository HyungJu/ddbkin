<template>
  <div id="app">
    <Main />
    <Second />
    <Third />
    <Forth />
  </div>
</template>

<script>
import Main from './pages/Main.vue'
import Second from './pages/Second.vue'
import Third from './pages/Third.vue'
import Forth from './pages/Forth.vue'
import AOS from 'aos'
import 'aos/dist/aos.css'

export default {
  name: 'App',
  components: {
    Main,
    Second,
    Third,
    Forth
  },
  created () {
    AOS.init()
  }
}


</script>

<style>
  #app{
    margin: 0;
    padding: 0;
  }
  body{
    margin:0;
    padding:0;
  }
</style>
