<template>
  <h1>{{ msg }}</h1>
</template>

<script>
export default {
  name: 'TestComponent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-size: 20px;
}
</style>
