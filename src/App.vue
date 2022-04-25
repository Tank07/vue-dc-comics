<template>
  <div id="app">
    <TotalHeader/>
    <JumboblaTron/>
    <BlackStripe/>
    <LogosList/>
    <FooterTotalFirst/>
    <FooterLast/>
  </div>
</template>

<script>
import TotalHeader from './components/TotalHeader.vue'
import JumboblaTron from './components/JumboblaTron.vue'
import BlackStripe from './components/BlackStripe.vue'
import LogosList from './components/LogosList.vue'
import FooterTotalFirst from './components/FooterTotalFirst.vue'
import FooterLast from './components/FooterLast.vue'

import "bootstrap"

export default {
  name: 'App',
  components: {
    TotalHeader,
    JumboblaTron,
    BlackStripe,
    LogosList,
    FooterTotalFirst,
    FooterLast
  }
}
</script>

<style >

@import "bootstrap/dist/css/bootstrap.min.css";

ul {
    list-style-type: none;
}

</style>
