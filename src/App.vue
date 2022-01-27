<template>
  <div id="app">
    <header-box/>
    <main-content-up/>
    <main-content-down/>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import MainContentUp from './components/MainContentUp.vue'
import MainContentDown from './components/MainContentDown.vue'


export default {
  name: 'App',
  components: {
    HeaderBox,
    MainContentUp,
    MainContentDown,
  }
}
</script>

<style lang="scss">
  @import './style/main.scss'
  
</style>
