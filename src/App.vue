<template>
  <div id="app">
    <h1 class="title is-1">Exemplo WebRTC</h1>
    <web-rtc-component />
  </div>
</template>

<script>
import WebRtcComponent from './components/WebRtcComponent.vue'

export default {
  name: 'app',
  components: {
    WebRtcComponent
  }
}
</script>

<style>

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
