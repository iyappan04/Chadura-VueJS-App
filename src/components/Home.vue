<template>

    <div class="home">
        <div class="home-content">
            <p>Start With Startup</p>
            <h1>Grow Your Business Using Our Services</h1>
            <button class="btn">Contact US</button>
        </div>
        <div class="home-img">
            <img src="https://softwareassist.netlify.app/img/banner_img.png" alt="">
        </div>
    </div>

</template>

<script>

export default {
    name: "Home",
}

</script>

<style scoped>
  

    .home{
        display: grid;
        grid-template-columns: 1fr 1fr;
        padding: 10rem 10rem;
    }

    .btn{
        background-color: rgb(64, 131, 233);
        color: white;
        font-weight: bold;
        border-radius: 1rem;
        border: none;
        outline: none;
        padding: 1.5rem 3rem;
    }
    h1{
        font-size: 5rem;
    }
    .home-img{
        align-items: center;
        text-align: center;
    }
   

</style>
