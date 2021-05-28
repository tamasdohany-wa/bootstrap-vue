<template>
  <section>
    <i class="bi bi-bug-fill"></i>
  </section>
</template>

<script>
import Vue from 'vue'
import { BootstrapVue } from 'bootstrap-vue'

export default {
  components: {
    BootstrapVue
  }
}
Vue.use(BootstrapVue)
</script>

<style scoped>
section {
  min-height: 100vh;
  display: grid;
  place-content: center;
  text-align: center;
}
section svg {
  margin: .25rem 0;
}
</style>
