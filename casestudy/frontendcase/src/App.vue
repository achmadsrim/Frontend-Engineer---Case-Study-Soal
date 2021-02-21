<template>
  <div id="app">
    <Formuser />
  </div>
</template>

<script>
import Formuser from './components/Formuser.vue'

export default {
  name: 'App',
  components: {
    Formuser
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
