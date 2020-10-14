<template>
  <div id="app">
    <layout></layout>
  </div>
</template>

<script>
import Layout from '@/layout/index'
export default {
  name: 'App',
  components: {
    Layout,
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
}

body, html, #app {
  margin: 0;
  padding: 0;
  height: 100%;
}
</style>
