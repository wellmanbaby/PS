<template>
  <div id="app">
    <bar></bar>
    <div id="mian">
     <router-view/>
    </div>
  </div>
</template>

<script>
import bar from './components/commen/bar'

export default {
  name: 'App',
  components:{
    bar
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
}
</style>
