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

section{
  display: flex;
  background-color: grey;
  align-items: center;
  justify-content: space-between;
  padding-left: 20%;
  padding-right: 20%;
}

</style>