<template>
  <div id="app">
    <TheHeader/>
    <router-view/>
  </div>
</template>

<script>
// @ is an alias to /src
import TheHeader from '@/components/TheHeader.vue'

export default {
  name: 'home',
  components: {
    TheHeader
  }
}
</script>


<style lang="scss">
  body {
    margin: 0;
  }
  a {
    text-decoration: none;
  }
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
</style>
