<template>
    <section class="hero is-fullheight">
        <div class="hero-body">
            <div class="cont">
                <img src="../assets/logo.png" alt="">
                <p class="title is-1">
                    Welcome Template Stock
                </p>
                <p class="content px-6">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.<br>
                    Modi nemo, ea omnis architecto cumque? Necessitatibus.<br>
                    Lorem ipsum dolor sit amet.
                </p>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name: 'hero',
    data() {
        return {
            // css:
        }
    }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*@import '../assets/css/style.css';*/
.hero img {
    width: auto;
    margin-bottom: 1rem;
    /*height:10vh;*/
}

.hero .hero-body {
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    background: linear-gradient(rgba(50, 48, 50, 0.7), rgba(50, 48, 48, 0.9)), url("../assets/bg.jpg") no-repeat center/cover;
}

.hero .hero-body .title {
    color: white;
}

.hero .hero-body .content {
    color: white;
}
</style>