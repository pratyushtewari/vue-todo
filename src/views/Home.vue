<template>
  <div class="home">
    <img alt="logo" src="../assets/logo.svg">
    <TestComponent msg="This is a test message"/>
  </div>
</template>

<script>
// @ is an alias to /src
import TestComponent from '@/components/TestComponent.vue'

export default {
  name: 'home',
  components: {
    TestComponent
  }
}
</script>

<style scoped>
img {
  width: 100px;
}
</style>

