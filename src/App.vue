<template>
  <div id="app">
    <header-box/>
    <main-content-up/>
    <main-content-down/>
    <footer-up/>
    <footer-down/>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import MainContentUp from './components/MainContentUp.vue'
import MainContentDown from './components/MainContentDown.vue'
import FooterUp from './components/FooterUp.vue'
import FooterDown from './components/FooterDown.vue'


export default {
  name: 'App',
  components: {
    HeaderBox,
    MainContentUp,
    MainContentDown,
    FooterUp,
    FooterDown,
  }
}
</script>

<style lang="scss">
  @import './style/main.scss'
  
</style>
