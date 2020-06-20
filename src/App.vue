<template>
  <div id="app">
    <my-button text="My Library Button"></my-button>
  </div>
</template>

<script>
import MyButton from './components/button.vue'

export default {
  name: 'App',
  components: {
    MyButton
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
