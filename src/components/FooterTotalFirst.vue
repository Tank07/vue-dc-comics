<template>
  <footer>

    <div>
      <FooterMenuList/>
    </div>
    <div>
      <FooterLogo/>
    </div>

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
}

</style>