<template>
  <div id="app">
    <div class="main-container">
      <geometric-squares></geometric-squares>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import GeometricSquares from './components/GeometricSquares.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    GeometricSquares
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
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

.main-container {
  background: #FFF9E3;
  width: 95%;
  height: 95vh;
}
</style>
