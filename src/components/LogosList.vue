<template>
  <div>
      
    <ul class="text-uppercase">
      <li><img src="../assets/img/buy-comics-digital-comics.png" alt="">digital comics</li>
      <li><img src="../assets/img/buy-comics-merchandise.png" alt="">dc merchandise</li>
      <li><img src="../assets/img/buy-comics-subscriptions.png" alt="">subscription</li>
      <li><img src="../assets/img/buy-comics-shop-locator.png" alt="">comic shop locator</li>
      <li><img src="../assets/img/buy-dc-power-visa.svg" alt="">dc power visa</li>
      
    </ul>

  </div>
</template>

<script>
export default {
  name: 'LogosList',
}
</script>

<style scoped>

  img{
    height: 40px;
    width: auto;
  }

  ul{
    background-color: #0282f9;
    display: flex;
    margin: auto;
    justify-content: space-between;
    align-items: center;
    padding-left: 20%;
    padding-right: 20%;
    height: 150px;
  }

  li{
    margin-left: 5px;
  }  

</style>