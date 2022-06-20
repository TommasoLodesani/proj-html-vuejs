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
    // position: relative;
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

        .line{
            width: 41%;
            border: dotted 1px #67615a;
        }
    }

    .caption {
        display: flex;
        justify-content: center;

        .product {
            text-align: center;
            flex-basis: calc(100% / 3);

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
                max-width: 345px;
            }

        }
    }

}
</style>