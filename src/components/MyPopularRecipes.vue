<template>
    <div class="section-container">

        <h3>POPULAR RECIPES</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Et, officia dignissimos</p>

        <div class="container-column">

            <div class="left">
                <img src="../assets/img/Yogurt-Nan-600x395.jpg" alt="immagine yougurt">
                <div class="caption">

                    <div class="title">

                        <h3>Lunch Favorite with Salad, Naan, And Beans</h3>
                        <h5>Bakery, Feauterd, Healthy, Latest Recipes, Staff Picks</h5>

                    </div>

                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem numquam ex dolorum distinctio
                        asperiores cupiditate placeat quas. Architecto, neque blanditiis! Nihil, voluptatibus. Neque
                        facere quibusdam suscipit corporis, sed quas libero.</p>

                    <button>LEARN MORE</button>

                </div>
            </div>

            <div class="right">

                <div class="container-img">
                    <img src="../assets/img/Mixed-fruits-400x263.jpg" alt="immagine frutta mista">

                </div>
                <div class="container-img">
                    <img src="../assets/img/r-rachel-park-366508-unsplash-min-400x263.jpg" alt="immagine frutta mista">

                </div>
                <div class="container-img">
                    <img src="../assets/img/r-michelle-tsang-500721-unsplash-min-400x263.jpg" alt="immagine frutta mista">

                </div>
                <div class="container-img">
                    <img src="../assets/img/quick-summer-drink-460x295.jpg" alt="immagine frutta mista">

                </div>
                <div class="container-img">
                    <img src="../assets/img/r-maarten-van-den-heuvel-400626-unsplash-min-460x295.jpg" alt="immagine frutta mista">

                </div>
                <div class="container-img">
                    <img src="../assets/img/perfect-cosmopolitan-460x295.jpg" alt="immagine frutta mista">

                </div>
                <div class="container-img">
                    <img src="../assets/img/fi2x-6-460x295.jpg" alt="immagine frutta mista">

                </div>
                <div class="container-img">
                    <img src="../assets/img/r-brooke-lark-96398-unsplash-min-460x295.jpg" alt="immagine frutta mista">

                </div>

              


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
.section-container {
    width: 65%;
    margin: 55px auto;
    text-align: center;

    h3 {
        margin-bottom: 30px;
        font-weight: 100;
    }

    p {
        color: #67615a;
        margin-bottom: 40px;
    }


    .container-column {
        display: flex;
        flex-basis: 50%;
        justify-content: space-between;

        .left {
            text-align: left;

            .caption {
                width: 600px;
                background-color: white;
                padding: 45px 35px;

                p {
                    line-height: 1.8;
                    padding-top: 25px;
                }

                button {
                    background-color: #fc7523;
                    border: none;
                    border-radius: 2px;
                    color: white;
                    padding: 13px 32px;
                    text-align: center;
                    text-decoration: none;
                    display: inline-block;
                    font-size: 14px;
                    font-weight: bold;
                }

                .title {
                    border-bottom: dotted 1px #67615a;

                    h3 {
                        font-weight: 100;
                        margin-bottom: 10px;
                    }

                    h5 {
                        font-weight: 100;
                        color: #67615a;
                        padding-bottom: 25px;
                    }

                }

            }
        }



        .right {
            display: flex;
            flex-wrap: wrap;
            margin-left: 45px;

            .container-img {
                margin-bottom: 5px;
                margin-right: 25px;
                flex-basis: calc((100% - 50px)/ 2);


                img {
                    max-width: 100%;
                }

            }


        }
    }


}
</style>