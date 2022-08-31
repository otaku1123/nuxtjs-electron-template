<template>
  <!-- <Tutorial /> -->
  <button @click="hello()">hello world</button>
</template>

<!-- <script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script> -->
<script>
export default {
  methods: {
    hello() {
      // console.log('hello world')
      window.api.hello()
    }
  },
}
</script>
