<template>
  <div id="app">
    <TotalHeader/>
    <BlackStripe/>
    <LogosList/>
    <FooterTotalFirst/>
    <FooterLast/>
  </div>
</template>

<script>
import TotalHeader from './components/TotalHeader.vue'
import BlackStripe from './components/BlackStripe.vue'
import LogosList from './components/LogosList.vue'
import FooterTotalFirst from './components/FooterTotalFirst.vue'
import FooterLast from './components/FooterLast.vue'

export default {
  name: 'App',
  components: {
    TotalHeader,
    BlackStripe,
    LogosList,
    FooterTotalFirst,
    FooterLast
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
