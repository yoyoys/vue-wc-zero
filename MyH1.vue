<template>
  <h1>Hello! {{name}}!</h1>
</template>

<script lang="ts">
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
