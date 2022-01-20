<template>
<Header msg="Weeeeelcome to Your Vue.js App"/>
<View/>
<Button msg="COUCOUUUU"></Button>
</template>

<script>
import Header from './components/Header.vue'
import View from './components/View.vue'
import Button from './components/Button.vue'
export default {
  name: 'App',
  components: {
    Header,
    View,
    Button
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
  margin-top: 60px;
}
</style>
