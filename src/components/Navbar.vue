<script>
export default {}
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
      <div class="icon">
        <img src="src\assets\icons\facebook.png" alt="">
        <img src="src\assets\icons\instagram.png" alt="">
        <img src="src\assets\icons\linkedin.png" alt="">
        <img src="src\assets\icons\twitter.png" alt="">
      </div>
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
  .icon {
    img{
      margin: 0 6px;
      height: 18px;
    }
  }
}





</style>

 


