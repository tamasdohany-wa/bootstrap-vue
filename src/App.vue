<template>
  <section>
    <b-icon icon="exclamation-circle-fill" variant="success" title="success"></b-icon>
    <b-icon icon="exclamation-circle-fill" variant="warning" title="warning"></b-icon>
    <b-icon icon="exclamation-circle-fill" variant="danger" title="danger"></b-icon>
    <b-icon icon="exclamation-circle-fill" variant="info" title="info"></b-icon>
    <b-icon icon="exclamation-circle-fill" variant="primary" title="primary"></b-icon>
    <b-icon icon="exclamation-circle-fill" variant="secondary" title="secondary"></b-icon>
    <b-icon icon="exclamation-circle-fill" variant="dark" title="dark"></b-icon>
  </section>
</template>

<script>
import Vue from 'vue'
import { BootstrapVueIcons } from 'bootstrap-vue'
import 'bootstrap/dist/css/bootstrap.css'

export default {
  name: 'App',
  components: {
    BootstrapVueIcons
  }
}
Vue.use(BootstrapVueIcons)
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
