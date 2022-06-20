<template>
    <div class="jumbo-image">

        <div class="title">

            <h1>Sbuscribe <span>&</span> Recive a Free eBook</h1>
           
            <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi sint provident rem et accusantium architecto delectus excepturi</h4>
            
            <div class="input-form">

                <input type="text" placeholder="Insert your email...*">
                <button>SUBSCRIBE</button>

            </div>

            <h5>ipsum dolor sit amet consectetur adipisicing</h5>
        </div>


    </div>
</template>

<script>
export default {
    name: 'MySubscribe'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbo-image {
    width: 100%;
    height: 612px;
    background-image: url("../assets/img/subscribe-sec-bg.png");
    background-color: white;
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
            margin-top: 20px;
            color: #67615a;
            font-weight: 100;

        }

        h5{
            margin-top: 20px;
            color: #67615a;
            font-weight: 100;

        }

        .input-form{
            margin-top: 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;

            input{
                width: 70%;
                padding: 20px;
                border-radius: 4px;
                border: solid 2px #f0eeeb;
                ::placeholder{
                    color:#f0eeeb ;
                }
            }
        }

        button {
            background-color: #fc7523;
            border: none;
            border-radius: 2px;
            color: white;
            padding: 20px 44px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 15px;
            font-weight: bold;
            margin-right: 35px;
        }

    }

 

   



}
</style>