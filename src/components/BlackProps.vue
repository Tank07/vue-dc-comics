<template>
  <div class="my-3">
      
      <img :src="thumb" alt="" class="img-fluid">
      <h5 class="text-white my-3">{{series}} </h5>
    
  </div>
</template>

<script>
export default {
  name: 'BlackProps',

   props: {
      thumb: String,
      series: String,
   }

}
</script>


<style scoped>

</style>[
  