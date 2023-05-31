<script>

  import Header from "./components/Header.vue"
  import Main from "./components/Main.vue"
  import Footer from "./components/Footer.vue"

  export default {
      components: {
        Header,
        Main,
        Footer,
      }
    }

</script>

<template>
<div class="container-fluid">
  <Header/>
  <Main/>
  <Footer/>
</div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


 </style>
