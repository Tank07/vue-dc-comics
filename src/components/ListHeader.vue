<template>
  <div>
      
    <ul class="fw-bold">
      <li>Characters</li>
      <li>Comics</li>
      <li>Movies</li>
      <li>Tv</li>
      <li>Games</li>
      <li>Collectibles</li>
      <li>Videos</li>
      <li>Fans</li>
      <li>News</li>
      <li>Videos</li>
    </ul>

  </div>
</template>

<script>
export default {
  name: 'ListHeader',
}
</script>

<style scoped>


ul {
    list-style-type: none;
    display: flex;    
}

li{
  margin: 0 5px;
}

</style>