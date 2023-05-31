<script>

</script>
<template>
    <div class="container">
        <div class="row">
            <div class="col-4 hero-text my-auto">
                <p class="sub-hero"><strong>I'M WINGMAN</strong></p>
                <h1>Peace On Earth A Wonderful Wish But No Way</h1>
                <p>
                    Success isn't overnight.It's when everyday you get a little better than the day before.It all adds up.
                </p>
                <button>   
                   <strong>Get Started For Free</strong>
                </button>
            </div>
            <div class="col-8 hero-image">
                <img src="src\assets\images\home-movation-hero-image.png" alt="">
            </div>

        </div>
    </div>
</template>

<style lang="scss" scoped>
.container {
    margin-top: 50px;
}
 .hero-text {
    // display: flex;
    // align-content: center;
    // align-items: center;
    // flex-direction: column;
    .sub-hero{
        font-family: "Times New Roman", Times, serif;
    }
    h1 {
        font-family: "Times New Roman", Times, serif;
    }
    button {
        background: #20ad96; 
        color:white;
        padding: 5px 25px;
        border-radius: 5px;
        border: none;
    }
 }

 .hero-image {
    display: flex;
    justify-content: center;
    background-image: url('src/assets/images/home-movation-shape-face-300x267.png');
        background-repeat: no-repeat;
        background-position: 60% 120%;
        background-size:50%;
    img {
        display:block;
       width: 50%;
       position:relative;
    }
 }
</style>

