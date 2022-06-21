<template>
    <div class="section-container">

        <h3>POPULAR RECIPES</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Et, officia dignissimos</p>

        <div class="container-column">

            <div class="left">
                <div class="image-container">
                    <img src="../assets/img/Yogurt-Nan-600x395.jpg" alt="immagine yougurt">

                    <div class="img-hoover">
                        <div class="text-hoover">

                            <h3>Lunch Favorite with Salad, Naan, And Beans</h3>

                        </div>
                    </div>


                </div>

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

                    <div class="img-hoover-right">
                        <div class="text-hoover-right">

                            <h3>Food Corner: Top Japanese restaurant for Sushi</h3>

                        </div>
                    </div>

                </div>
                <div class="container-img">
                    <img src="../assets/img/r-rachel-park-366508-unsplash-min-400x263.jpg" alt="immagine frutta mista">

                    <div class="img-hoover-right">
                        <div class="text-hoover-right">

                            <h3>Food Corner: Top Japanese restaurant for Sushi</h3>

                        </div>
                    </div>

                </div>
                <div class="container-img">
                    <img src="../assets/img/r-michelle-tsang-500721-unsplash-min-400x263.jpg" alt="immagine frutta mista">

                    <div class="img-hoover-right">
                        <div class="text-hoover-right">

                            <h3>Food Corner: Top Japanese restaurant for Sushi</h3>

                        </div>
                    </div>

                </div>

                <div class="container-img">
                    <img src="../assets/img/quick-summer-drink-460x295.jpg" alt="immagine frutta mista">
                    <div class="img-hoover-right">
                        <div class="text-hoover-right">

                            <h3>Food Corner: Top Japanese restaurant for Sushi</h3>

                        </div>
                    </div>

                </div>

                <div class="container-img">
                   <img src="../assets/img/r-maarten-van-den-heuvel-400626-unsplash-min-460x295.jpg"
                        alt="immagine frutta mista">
                    <div class="img-hoover-right">
                        <div class="text-hoover-right">

                            <h3>Food Corner: Top Japanese restaurant for Sushi</h3>

                        </div>
                    </div>

                </div>

                <div class="container-img">
                   <img src="../assets/img/perfect-cosmopolitan-460x295.jpg" alt="immagine frutta mista">
                    <div class="img-hoover-right">
                        <div class="text-hoover-right">

                            <h3>Food Corner: Top Japanese restaurant for Sushi</h3>

                        </div>
                    </div>

                </div>

                <div class="container-img">
                   <img src="../assets/img/fi2x-6-460x295.jpg" alt="immagine frutta mista">
                    <div class="img-hoover-right">
                        <div class="text-hoover-right">

                            <h3>Food Corner: Top Japanese restaurant for Sushi</h3>

                        </div>
                    </div>

                </div>

                <div class="container-img">
                   <img src="../assets/img/r-brooke-lark-96398-unsplash-min-460x295.jpg" alt="immagine frutta mista">
                    <div class="img-hoover-right">
                        <div class="text-hoover-right">

                            <h3>Food Corner: Top Japanese restaurant for Sushi</h3>

                        </div>
                    </div>

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

            .image-container {
                position: relative;

            }

            .image-container:hover .img-hoover {
                opacity: 1;
            }

            .img-hoover {
                position: absolute;
                top: 0;
                bottom: 0;
                left: 0;
                right: 0;
                height: 100%;
                width: 100%;
                opacity: 0;
                transition: .5s ease;
                background-image: linear-gradient(to bottom, rgba(255, 0, 0, 0), rgba(249, 105, 14, 1));
            }

            .text-hoover {
                font-size: 17px;
                position: absolute;
                top: 50%;
                left: 50%;
                -webkit-transform: translate(-50%, -50%);
                -ms-transform: translate(-50%, -50%);
                transform: translate(-50%, -50%);
                text-align: center;

                h3 {
                    color: white;
                    font-weight: bold;

                }
            }

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
                position: relative;

                img {
                    max-width: 100%;
                }

                &:hover .img-hoover-right {
                    opacity: 1;
                }

                .img-hoover-right {
                    position: absolute;
                    top: -6%;
                    bottom: 0;
                    left: 0;
                    right: 0;
                    height: 100%;
                    width: 100%;
                    opacity: 0;
                    transition: .5s ease;
                    background-image: linear-gradient(to bottom, rgba(255, 0, 0, 0), rgba(249, 105, 14, 1));
                }

                .text-hoover-right {

                    font-size: 17px;
                    position: absolute;
                    top: 50%;
                    left: 50%;
                    -webkit-transform: translate(-50%, -50%);
                    -ms-transform: translate(-50%, -50%);
                    transform: translate(-50%, -50%);
                    text-align: center;

                    h3 {
                        color: white;
                        font-weight: bold;

                    }
                }

            }


        }
    }


}
</style>