<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo_platcube.png">
    <HelloWorld msg="Welcome to PlatCube Homepage"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
