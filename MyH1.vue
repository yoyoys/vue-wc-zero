<template>
  <h1>Hello! {{name}}!</h1>
</template>

<script>
import Vue from 'vue'
export default Vue.extend({
  props: {
    name: {
      type: String,
      default: 'Yoyo'
    }
  }
})
</script>

<style lang="scss" scoped>
  h1 {
    color: #990000
  }
</style>

