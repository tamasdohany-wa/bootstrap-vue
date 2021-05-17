<template>
  <b-icon icon="exclamation-circle-fill" variant="success"></b-icon>
</template>

<script>
import Vue from 'vue'
import { BootstrapVueIcons } from 'bootstrap-vue'
export default {
  name: 'App',
  components: {
    BootstrapVueIcons,
  }
}
Vue.use(BootstrapVueIcons)
</script>

<style>
svg {
  fill: red;
}
</style>
