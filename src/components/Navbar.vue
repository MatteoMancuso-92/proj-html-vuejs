<script>
import Social from "/src/components/Social.vue"
  export default {
      components: {
        Social,
      }
    }
</script>
<template>
   <div class="container">
   <nav>
      <div class="logo">
        <img src="../assets/images/dark-logo.png" alt="">
      </div>
      <div class="center-bar">
        <a href="">Home</a>
        <a href="">Pages</a>
        <a href="">Courses</a>
        <a href="">Features</a>
        <a href="">Blog</a>
        <a href="">Shop</a>
      </div>
      <Social />
    </nav>
  </div>
</template>

<style lang="scss" scoped>
nav {
  display: flex;
  justify-content: space-between;
  margin-top: 10px;
  .logo {
    img {
      height: 18px;}
    }
  .center-bar {
    a{
      color:black;
      margin: 0 10px;
    }
  }
  
}





</style>

 


