<template>
  <div>
      
    <ul>
      <li><h3>FOLLOW US</h3></li>
      <li><img src="../assets/img/footer-twitter.png" alt=""></li>
      <li><img src="../assets/img/footer-facebook.png" alt=""></li>
      <li><img src="../assets/img/footer-youtube.png" alt=""></li>
      <li><img src="../assets/img/footer-periscope.png" alt=""></li>
      <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
      
    </ul>

  </div>
</template>

<script>
export default {
  name: 'FooterSocials',
}
</script>

<style scoped>

  ul{
    display: flex;
    align-items: center;
  }

  li{
    margin: 0 5px;
  }

  img{
    height: 30px;
    width: auto;
  }  

</style>