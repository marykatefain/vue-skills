<!-- HTML goes in Template section -->
<template>
  <div id="app">
    <!-- "Skills" here is referenceing the name of a component -->
    <Skills />
  </div>
</template>

<!-- Logic of the app -->
<script>
// We must import Skills component
import Skills from './components/Skills.vue'

export default {
  name: 'app',
  components: {
    Skills
  }
}
</script>

<!-- CSS -->
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
