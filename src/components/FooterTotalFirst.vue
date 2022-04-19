<template>
  <footer>

      <FooterMenuList/>
      <FooterLogo/>

  </footer>
</template>

<script>
import FooterMenuList from './FooterMenuList.vue'
import FooterLogo from './FooterLogo.vue'

export default {
  name: 'FooterTotalFirst',
  components: {
    FooterMenuList,
    FooterLogo,
  }
}
</script>

<style scoped>

footer{
  display: flex;
  padding-left: 20%;
  padding-right: 20%;
  background-image: url("../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
}

</style>