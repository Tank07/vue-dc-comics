<template>
  <div id="app">
    <TotalHeader/>
    <BlackStripe/>
    <LogosList/>
    <FooterMenuList/>
  </div>
</template>

<script>
import TotalHeader from './components/TotalHeader.vue'
import BlackStripe from './components/BlackStripe.vue'
import LogosList from './components/LogosList.vue'
import FooterMenuList from './components/FooterMenuList.vue'

export default {
  name: 'App',
  components: {
    TotalHeader,
    BlackStripe,
    LogosList,
    FooterMenuList
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
