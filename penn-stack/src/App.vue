<template>
  <div id="app">
   <Header></Header>
   <router-view></router-view>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import Home from '@/views/Home.vue'

export default {
  name: 'home',
  components: {
    Header,
    Home
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
  margin-top: 0px;
}
</style>

