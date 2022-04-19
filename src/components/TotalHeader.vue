<template>
  <header>

    <div class="col">
      <LogoHeader/>
    </div>
    <div class="col">
      <ListHeader/>
    </div>
  </header>
</template>

<script>
import LogoHeader from './LogoHeader.vue'
import ListHeader from './ListHeader.vue'
export default {
  name: 'TotalHeader',
  components: {
    LogoHeader,
    ListHeader,
  }
}
</script>



<style scoped>

  header{
    display: flex;
    margin: auto;
    justify-content: space-between;
    align-items: center;
    padding-left: 20%;
    padding-right: 20%;
  }

</style>