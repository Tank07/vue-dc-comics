<template>
  <section>

    <div>
      <FooterButton/>
    </div>
    <div>
      <FooterSocials/>
    </div>
    
  </section>
</template>

<script>
import FooterButton from './FooterButton.vue'
import FooterSocials from './FooterSocials.vue'


export default {
  name: 'FooterLast',
  components: {
    FooterButton,
    FooterSocials
  }
}
</script>

<style scoped>


</style>