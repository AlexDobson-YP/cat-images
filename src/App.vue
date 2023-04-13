<template>
  <div id="app">
    <RandomImage />
  </div>
</template>

<script>
import RandomImage from './components/RandomImage.vue'

export default {
  name: 'App',
  components: {
    RandomImage
  }
}
</script>

<style>
html,
body {
  margin:0;
  padding:0;
}

#app {
  width: 100vw;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
