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
<style scoped>
  @import url('https://fonts.googleapis.com/css?family=Montserrat:400,700');

  body {
  background-color: #EEEEEE;
  font-family: 'Montserrat', sans-serif;
  display: grid;
  grid-template-rows: auto;
  justify-items: center;
  align-items: center;
  }
  body, html {
  margin: 0;
  height: 100%;
  }
  #app {
    width: 50%;
  }
</style>
