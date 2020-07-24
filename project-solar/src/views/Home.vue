<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Project Solar"/>
    <p>Test</p>
    <p>Test2</p>
    <p>Test3</p>
    <p>Test4</p>
    <p>Test5</p>
    <p>Test6</p>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
  p {
    padding:50px;
  }
</style>
