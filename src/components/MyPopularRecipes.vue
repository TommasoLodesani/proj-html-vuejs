<template>
    <div class="section-container">

        <h3>POPULAR RECIPES</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Et, officia dignissimos</p>

        <div class="container-column">

            <div class="left">
                <img src="../assets/img/Yogurt-Nan-600x395.jpg" alt="immagine yougurt">
                <div class="caption">

                </div>
            </div>

            <div class="right">

                <img src="../assets/img/Mixed-fruits-200x132.jpg" alt="immagine frutta mista">
                <img src="../assets/img/r-rachel-park-366508-unsplash-min-200x132.jpg" alt="immagine frutta mista">
                <img src="../assets/img/r-michelle-tsang-500721-unsplash-min-200x132.jpg" alt="immagine frutta mista">
                <img src="../assets/img/r-michelle-tsang-500721-unsplash-min-200x132.jpg" alt="immagine frutta mista">
                <img src="../assets/img/Mixed-fruits-200x132.jpg" alt="immagine frutta mista">
                <img src="../assets/img/Mixed-fruits-200x132.jpg" alt="immagine frutta mista">
                <img src="../assets/img/Mixed-fruits-200x132.jpg" alt="immagine frutta mista">
                <img src="../assets/img/Mixed-fruits-200x132.jpg" alt="immagine frutta mista">
                
                
            </div>
        </div>

        


    </div>
</template>

<script>
export default {
    name: 'MyPopularRecipes'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.section-container{
    width: 65%;
    margin: auto;
    text-align: center;
    h3{
        margin-bottom: 30px;
    }

    p{
        color:#67615a ;
        margin-bottom: 40px;
    }


    .container-column{
        display: flex;
        flex-basis: 50%;
        justify-content: space-between;
        


        .right{
            display: flex;
            flex-basis: 40%;
            flex-wrap: wrap;
            margin-top: -6px;
            img{
                padding: 6px;
            }


        }
    }


}

</style>