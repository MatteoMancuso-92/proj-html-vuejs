<script>
export default {}
   

</script>

<template>

    <nav>
      <div class="logo">
        <img src="../../public/images/dark-logo.png" alt="">
      </div>

      <div class="topnav">
        <a href="">Home</a>
        <a href="">Pages</a>
        <a href="">Courses</a>
        <a href="">Features</a>
        <a href="">Blog</a>
        <a href="">Shop</a>
      </div>

      <div class="icon">
        <font-awesome-icon :icon="['fab', 'facebook']" />

      </div>
    </nav>
    
</template>

<style lang="scss" scoped>

.navbar {
  display: flex;
}

img {
  height: 18px;
}

 .topnav { overflow: hidden;}

/* Style the links inside the navigation bar */
.topnav a {
    
    color: black;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
}

/* Change the color of links on hover */
.topnav a:hover {
  background-color: #ddd;
    color: violet;
}

</style>

 


