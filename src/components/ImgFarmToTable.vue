<template>
    <div class="section-container">

        <div class="container-column">

            <div class="left">

                <div class="big-img-section">

                    <img src="../assets/img/single-post-img3-800x527.jpg" alt="immagine yougurt">
                    <div class="title">

                        <h3>Lunch Favorite with Salad, Naan, And Beans</h3>
                        <h5>Bakery, Feauterd, Healthy, Latest Recipes, Staff Picks</h5>

                    </div>

                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem numquam ex dolorum distinctio
                        asperiores cupiditate placeat quas. Architecto, neque blanditiis! Nihil, voluptatibus. Neque
                        facere quibusdam suscipit corporis, sed quas libero.</p>

                    <h4>
                        Read Moere >
                    </h4>


                </div>

                <div class="small-img-section">

                    <div class="product">
                        <img src="../assets/img/single-post-img3-400x263.jpg" alt="immagine cibo">
                        <h3>Food Corner: Top Japanese restaurant for Sushi</h3>
                        <h6>By Admin, I March 2022</h6>
                    </div>
                    <div class="product">
                        <img src="../assets/img/fi-roundup-400x263.jpg" alt="immagine cibo">
                        <h3>Food Corner: Top Japanese restaurant for Sushi</h3>
                        <h6>By Admin, I March 2022</h6>
                    </div>
                    <div class="product">
                        <img src="../assets/img/fi-toasts-400x263.jpg" alt="immagine cibo">
                        <h3>Food Corner: Top Japanese restaurant for Sushi</h3>
                        <h6>By Admin, I March 2022</h6>
                    </div>
                    <div class="product">
                        <img src="../assets/img/single-post-img3-400x263.jpg" alt="immagine cibo">
                        <h3>Food Corner: Top Japanese restaurant for Sushi</h3>
                        <h6>By Admin, I March 2022</h6>
                    </div>
                    <div class="product">
                        <img src="../assets/img/fi-roundup-400x263.jpg" alt="immagine cibo">
                        <h3>Food Corner: Top Japanese restaurant for Sushi</h3>
                        <h6>By Admin, I March 2022</h6>
                    </div>
                    <div class="product">
                        <img src="../assets/img/fi-toasts-400x263.jpg" alt="immagine cibo">
                        <h3>Food Corner: Top Japanese restaurant for Sushi</h3>
                        <h6>By Admin, I March 2022</h6>
                    </div>

                </div>

                <div class="button">LOAD MORE POSTS</div>


            </div>

            <div class="right">

            </div>
        </div>




    </div>
</template>

<script>
export default {
    name: 'ImgFarmToTable'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.section-container {
    width: 65%;
    margin: 55px auto;

    .container-column {
        display: flex;
        justify-content: space-between;

        .left {

            width: 64%;


            .big-img-section {
                width: 100%;
                background-color: white;
                // padding: 45px 35px;

                img {
                    max-width: 100%;
                }

                .title {
                    border-bottom: dotted 1px #67615a;
                    margin: 25px;

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

                p {
                    line-height: 1.8;
                    padding: 25px;
                    margin-top: -30px;
                    color: #67615a;
                }

                h4 {
                    color: #67615a;
                    text-decoration: none;
                    font-size: 12px;
                    padding: 25px;
                    margin-bottom: 40px;

                }

            }

            .small-img-section {
                display: flex;
                flex-wrap: wrap;
                margin: 0 -20px;
                .product {
                    text-align: center;
                    flex-basis: calc((100% - 80px )/ 2);
                    margin: 0 20px;
                    margin-bottom: 40px;
                    padding-bottom: 40px;
                    background-color: white;
    
                    h3 {
                        padding: 15px 25px;
                        font-weight: 100;
                        color: #333338;
    
                    }
    
                    h6 {
                        color: #67615a;
                        font-weight: 100
                    }
    
                    img {
                        max-width: 100%;
                    }
    
                }


            }

            .button{
                text-align: center;
                width: 100%;
                background-color: #edede7;
                padding: 15px;
                font-weight: bold;
            }


        }



        .right {
            display: flex;
            flex-wrap: wrap;
            margin-left: 45px;

            .container-img {
                margin-bottom: 25px;
                margin-right: 25px;
                flex-basis: calc((100% - 50px)/ 2);


                img {
                    max-width: 100%;
                }

            }

            // margin-top: -6px;
            // img{
            //     padding: 6px;
            // }


        }
    }


}
</style>