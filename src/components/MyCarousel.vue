<template>
    <div class="img-container">
        <img src="../assets/img/Yogurt-Nan-400x263.jpg" alt="">
        <img src="../assets/img/Mixed-fruits-460x295.jpg" alt="">
        <img src="../assets/img/r-rachel-park-366508-unsplash-min-400x263.jpg" alt="">
        <img src="../assets/img/r-michelle-tsang-500721-unsplash-min-400x263.jpg" alt="">
       
    </div>
</template>

<script>
export default {
    name: 'MyCarousel'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.img-container{
    display: flex;
    img{
        flex-basis: calc(100% / 4);
        max-width: 100%;
    }
}

</style>