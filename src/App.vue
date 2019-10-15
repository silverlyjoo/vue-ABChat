<template>
  <div id="app">
    <abchat :base_url="'http://13.124.235.242:5000'"></abchat>
  </div>
</template>

<script>
import abchat from '@/components/vue-abchat.vue'

export default {
  name: 'app',
  components: {
    abchat
  }
}
</script>

<style>
</style>
