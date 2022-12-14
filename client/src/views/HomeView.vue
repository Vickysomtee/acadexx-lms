<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <div class="justify-center flex bg-blue-300 items-center h-screen">Us</div>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
