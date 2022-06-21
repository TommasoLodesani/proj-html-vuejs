<template>
    <div class="container">

        <div class="box">
            <div class="title">
                <div class="line"></div>
                <h3>FOODIE JOURNAL</h3>
                <div class="line"></div>
            </div>
            <div class="caption">
                <div class="product">
                    
                    <div class="img-container">
                        <img src="../assets/img/single-post-img3-400x263.jpg" alt="immagine cibo">

                        <div class="img-hoover">
                            <div class="text-hoover">
                                
                                <h3>Food Corner: Top Japanese restaurant for Sushi</h3>

                            </div>
                        </div>
                    </div>
                    <h3>Food Corner: Top Japanese restaurant for Sushi</h3>
                    <h6>By Admin, I March 2022</h6>
                    
                </div>
                <div class="product">
                    <div class="img-container">
                        <img src="../assets/img/fi-roundup-400x263.jpg" alt="immagine cibo">

                        <div class="img-hoover">
                            <div class="text-hoover">
                                
                                <h3>Roundup: My New Favourite Recipes For Healthy Living</h3>

                            </div>
                        </div>
                    </div>
                    <h3>Roundup: My New Favourite Recipes For Healthy Living</h3>
                    <h6>By Admin, I March 2022</h6>
                    
                </div>
                
                <div class="product">
                    <div class="img-container">
                        <img src="../assets/img/fi-toasts-400x263.jpg" alt="immagine cibo">

                        <div class="img-hoover">
                            <div class="text-hoover">
                                
                                <h3>Why These Toast With Tea are My New Favourite</h3>

                            </div>
                        </div>
                    </div>
                    <h3>Why These Toast With Tea are My New Favourite</h3>
                    <h6>By Admin, I March 2022</h6>
                    
                </div>
               

               
                


            </div>
        </div>


    </div>
</template>

<script>
export default {
    name: 'FoodieJournal'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.box {
    width: 65%;
    margin: auto;
    padding: 35px;
    // height: 470px;
    background-color: white;
    position: relative;
    margin-top: -50px;
    // top: 37%;
    // left: 50%;
    // transform: translate(-50%, -50%);

    .title {
        text-align: center;
        padding-bottom: 35px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-left: 25px;
        padding-right: 25px;

        h3 {
            font-weight: 100;
            color: #333338;


        }

        .line {
            width: 41%;
            border: dotted 1px #67615a;
        }
    }

    .caption {
        display: flex;
        justify-content: center;

        .product {

            text-align: center;
            flex-basis: calc((100% - 30px) / 3);
            margin: 0 10px;

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

            .img-container {
                position: relative;

            }

            .img-container:hover .img-hoover {
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
                background-image: linear-gradient(to bottom, rgba(255,0,0,0), rgba(249,105,14,1));
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

                h3{
                    color: white;
                    font-weight: bold;

                }
            }

        }
    }

}
</style>