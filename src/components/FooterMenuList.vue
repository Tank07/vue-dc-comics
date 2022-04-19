<template>
  <section>

    <div>
      <FooterFirstList/>
    </div>
    <div>
      <FooterSecondList/>
    </div>
    <div>
      <FooterThirdList/>
    </div>
  </section>
</template>

<script>
import FooterFirstList from './FooterFirstList.vue'
import FooterSecondList from './FooterSecondList.vue'
import FooterThirdList from './FooterThirdList.vue';
export default {
  name: 'FooterMenuList',
  components: {
    FooterFirstList,
    FooterSecondList,
    FooterThirdList
  }
}
</script>

<style scoped>

section{
    display: flex;
}

</style>