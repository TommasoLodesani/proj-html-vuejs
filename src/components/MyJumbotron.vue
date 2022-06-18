<template>
    <div class="jumbo-image">

        <div class="title">

            <h1>Food Corner: Top Japanese Resturans for Sushi</h1>
            <h5>March 25,2019</h5>

        </div>

    </div>
</template>

<script>
export default {
    name: 'MyJumbotron'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbo-image {
    width: 100%;
    height: 700px;
    background-image: url("../assets/img/single-post-img3-1200x790.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;


    .title {
        text-align: center;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        padding: 50px;
        background-color: white;

    }

}
</style>