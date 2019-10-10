<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <SampleFile/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import SampleFile from '@/components/SampleFile.vue'

export default {
  name: 'home',
  components: {
    HelloWorld,
    SampleFile
  }
}
</script>
