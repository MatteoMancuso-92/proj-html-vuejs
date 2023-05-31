<script>
import Social from "/src/components/Social.vue"

  export default {
      components: {
        Social,
      },
      data() {
    //let gianni = [uno,due,tre]
    return {
      menus:[
        {title: 'Home', href: 'Home.html'},
        {title: 'Pages', href:'Pages.html'},
        {title: 'Courses', href: 'Courses.html'},
        {title: 'Features', href: 'Features.html'},
        {title: 'Blog', href:'Blog.html'},
        {title: 'Shop', href: 'Shop.html'},
      ],
    };
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
        <a v-for="(menu,i) in menus" :key="i" :href="menu.href">
          {{ menu.title }}
        </a>
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
    list-style-type: none;
    a{
      color:black;
      margin: 0 10px;
    }
  }
  
}





</style>

 


