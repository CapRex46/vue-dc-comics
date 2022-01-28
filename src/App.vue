<template>
  <div id="app">
    <header-box :nav="nav"/>
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
  },
  data () {
    return {
      nav: [
        {
          id: '3449734825',
          label: 'CHARACTERS',
          url: '/',
        },
        {
          id: '0528301059',
          label: 'COMICS',
          url: '/',
        },
        {
          id: '0261945441',
          label: 'MOVIES',
          url: '/',
        },
        {
          id: '7811209593',
          label: 'TV',
          url: '/',
        },
        {
          id: '5274226812',
          label: 'GAMES',
          url: '/',
        },
        {
          id: '0448171797',
          label: 'COLLECTIBLES',
          url: '/',
        },
        {
          id: '2213265722',
          label: 'VIDEOS',
          url: '/',
        },
        {
          id: '5619490108',
          label: 'TV',
          url: '/',
        },
      ]
    }
  }
  
}
</script>

<style lang="scss">
  @import './style/main.scss'
  
</style>
