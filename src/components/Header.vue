<script>
import Navbar from "./Navbar.vue"
import Jumbo from "./Jumbo.vue"
export default {
  components: {
    Navbar,
    Jumbo
  },

};
</script>

<template>

    <header>
            <Navbar />
            <Jumbo/>
    </header>
</template>

<style scoped>
  header  {
    background-image: url('./src/assets/images/background-pattern-wavify.png');
    
}

img {
  
}
 

</style>