<script>
import Social from "/src/components/Social.vue"
  export default {
      components: {
        Social,
      }
    }

</script>

<template>

    <div class="container-fluid">
      <div class="container">
        <div class="row">
          <div class="col-5">
            <div><strong>Address</strong></div>
            <ul>
              <li>382 NE 191st St # 87394 Miami,Fl 33179-3899</li>
              <li>+1(305)547-9909(9am - 5 pm EST,Monday - Friday)</li>
              <li>Support@maxcoach.com</li>
              <Social />
            </ul>
          </div>
          <div class="col-2">
            <div><strong>Explore</strong></div>
              <ul>
                <li>Start here</li>
                <li>Blog</li>
                <li>About us</li>
              </ul>

          </div>
          <div class="col-2">
            <div class="empty">salmon</div>
            <ul>
              <li>Success story</li>
              <li>Courses</li>
              <li>Contact Us</li>
            </ul>

            
            </div>   
          <div class="col-3">
            <div><strong>Information</strong></div>
              <ul>
                <li>Membership</li>
                <li>Purchase guide</li>
                <li>Privacy policy</li>
                <li>Terms of service</li>
              </ul>
            </div>       
          </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container-fluid {
    background-color: black;
    color: white;
   .container {
    display: flex;
    justify-content: center;
    }
    .row{
      margin-top: 10px;
    }
    .empty {
      color:black
    }
      .ul {
      flex-direction: column;
   
    }
      li {
        list-style: none;
    }
  }

  .icon {
    background-color: white;
  }
</style>
