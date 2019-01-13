<template>
  <div id="app">
    <circle-counter width="20rem" height="20rem"/>
  </div>
</template>

<script>
import CircleCounter from '@/CircleCounter.vue'

export default {
  name: 'app',
  components: {
    CircleCounter
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
