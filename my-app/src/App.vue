<template>
  <div id="app">
    <LandingPage />
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

import LandingPage from './pages/LandingPage'

export default {
  name: 'App',
  components: {
    LandingPage
  }
}
</script>

<style>
  @import './assets/styles/global.css';
</style>