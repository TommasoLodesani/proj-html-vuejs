<template>
    <div class="jumbo-image">

        <div class="title">

            <h1>Food Corner: Top Japanese</h1>
            <h1>Resturans for sushi</h1>
            <h4>March 25,2019</h4>

        </div>

        <div class="title-orange">
            <h4>TODAY'S PICK</h4>
        </div>

        <div class="tab_icon">
            <div class="tab top">
                <div>
                    <img src="../assets/img/icona dollaro.jpg" alt="">

                </div>
                <h5>Demos</h5> 
            </div>
            <div class="tab bottom">
                <div>
                    <img src="../assets/img/icona dollaro.jpg" alt="">

                </div>
    
                <h5>On Sale</h5>    
            </div>
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
        top: 45%;
        left: 50%;
        transform: translate(-50%, -50%);
        padding: 65px 86px;
        background-color: white;
        border-radius: 10px;

        h1{
            font-size: 40px;
            color:#333338;
            
        }
        h4{
            margin-top: 10px;
            color: #67615a;

        }

    }

    .title-orange{
        text-align: center;
        position: absolute;
        top: 27%;
        left: 50%;
        transform: translate(-50%, -50%);
        background-color: #fc7525;
        border-radius: 7px;
        padding: 12px 23px;
        color: white;
        box-shadow: 0px 11px 13px -14px #000000;

        

    }

    .tab_icon{
        text-align: center;
        position: absolute;
        top: -2%;
        left: 97%;
        transform: translate(-50%, -50%);
        border-radius: 7px;
        color: black;
        // box-shadow: 0px 11px 13px -14px #000000;

        img{
            width: 40px;
            
        }

        .tab{
            background-color: white;
            border-radius: 5px;
            padding: 10px;
            box-shadow: 0px 11px 23px -14px #000;
          
            
        }

        .tab.top{
            margin-bottom: 15px;
            
        }

    }



}
</style>