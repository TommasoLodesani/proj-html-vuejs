<template>
    <div class="section-container ">

        <h3>CULINARY COLLECTION</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Et, officia dignissimos</p>

        <div class="box">
            <div class="product">
                <img src="../assets/img/drinks-recipes.png" alt="immagine drink">
                <a href="#">
                    <h5>DRINKS</h5>

                </a>
            </div>
            <div class="product">
                <img src="../assets/img/soups-recipes.png" alt="immagine soup">
                <a href="#">
                    <h5>SOUPS</h5>

                </a>
            </div>
            <div class="product">
                <img src="../assets/img/baking-recipes.png" alt="immagine drink">
                <a href="#">
                    <h5>BAKERY</h5>

                </a>
            </div>
            <div class="product">
                <img src="../assets/img/dinner-recipes.png" alt="immagine drink">
                <a href="#">
                    <h5>DINNER</h5>

                </a>
            </div>
            <div class="product">
                <img src="../assets/img/healthy-recipes.png" alt="immagine drink">
                <a href="#">
                    <h5>HEALTHY</h5>

                </a>
            </div>
            <div class="product">
                <img src="../assets/img/staff-picks.png" alt="immagine drink">
                <a href="#">
                    <h5>STAFF PICKS</h5>

                </a>
            </div>
            <div class="product">
                <img src="../assets/img/premium-recipes.png" alt="immagine drink">
                <a href="#">
                    <h5>APPETISER</h5>

                </a>
            </div>
            <div class="product">
                <img src="../assets/img/quick-easy-recipes.png" alt="immagine drink">
                <a href="#">
                    <h5>QUICK & EASY</h5>

                </a>
            </div>
            
        </div>


    </div>
</template>

<script>
export default {
    name: 'CulinaryCollection'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.section-container {
    width: 65%;
    margin: auto;
    margin-top: 200px;
    text-align: center;

    h3 {
        margin-bottom: 30px;
        font-weight: 100;
    }

    p {
        color: #67615a;
        margin-bottom: 40px;
    }


    .box{
        display: flex;
        flex-wrap: wrap;
      

        .product{
            flex-basis: calc((100% - 160px)/ 4);
            background-color: white;
            margin: 20px;
            padding: 10px;
         

            img{
                max-width: 35%;
            }

            a{
                color: black;
                text-decoration: none;
            }

            h5{
                padding: 15px;

                &:hover{
                    background-color: #fc7525;
                }
            }
        }
    }

}
</style>