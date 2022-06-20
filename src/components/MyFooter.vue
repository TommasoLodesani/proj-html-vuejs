<template>
    <footer>

        <div class="top-footer">

            <div class="col first">

                <div class="container-img">
                    <img src="../assets/img/avada-food-logo-mob-2x.png" alt="">

                </div>

                <!-- icone -->

                <ul>
                    <li>
                        <a href="#">
                            <font-awesome-icon icon="fa-brands fa-twitter" />
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <font-awesome-icon icon="fa-brands fa-twitter" />
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <font-awesome-icon icon="fa-brands fa-twitter" />
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <font-awesome-icon icon="fa-brands fa-twitter" />
                        </a>
                    </li>
                </ul>

                
            </div>
            <div class="col second">
                <ul>
                    <li v-for="(link, inedx) in links" :key="inedx">
                        <a href="link.url" :class="link.current ? 'here' : ''"> {{ link.text }}</a>
                    </li>
                </ul>

            </div>
            <div class="col third">
                <h4>CONTACT</h4>

                <ul>
                    <li>
                        <a href="#">
                            <font-awesome-icon icon="fa-brands fa-twitter" />
                        </a>

                        <div>
                            775 New York Ave, Brooklyn, Kings, New York 11230

                        </div>

                    </li>
                    <li>
                        <a href="#">
                            <font-awesome-icon icon="fa-brands fa-twitter" />
                        </a>
                         <div>
                            +23 2223355

                        </div>
                    </li>
                    <li>
                        <a href="#">
                            <font-awesome-icon icon="fa-brands fa-twitter" />
                        </a>

                        <div>
                            info@aveda.com

                        </div>
                    </li>

                </ul>
            </div>
            <div class="col fourth">
                <h4>GET OUR APP!</h4>

                <a href="#">
                    <img src="../assets/img/download-android.png" alt="logo download android">

                </a>

                <a href="#">

                    <img src="../assets/img/download-app-store.png" alt="logo download android">
                </a>


            </div>
        </div>



    </footer>

</template>

<script>
export default {
    name: 'MyFooter',
    data() {
        return {
            links: [
                {
                    text: "Recipes",
                    url: "#",
                    current: false
                },
                {
                    text: "Places",
                    url: "#",
                    current: true
                },
                {
                    text: "Blog",
                    url: "#",
                    current: false
                },
                {
                    text: "About",
                    url: "#",
                    current: false
                },
                {
                    text: "Contac",
                    url: "#",
                    current: false
                },
            ]
        }
    }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.top-footer {
    display: flex;
    justify-content: center;
    width: 70%;
    margin: auto;


    .col{
        flex-basis: (100% / 5);
        padding: 0px 50px;
        margin-top: 75px;
        border-right: dotted 1px #94908b;

          h4{
            color: #fc7525;
            margin-bottom: 20px;
        }
    }


    .col.first {

        .container-img {
            margin-bottom: 50px;
        }

        ul{
            display: flex;

            li{
                padding: 10px;

                a{
                    color: #94908b;
                    font-size: 17px;
                }
            }
        
           
        }

    }

    .col.second{

        ul {
    list-style-type: none;

    li {

        padding: 20px 0;

        a {
            text-decoration: none;
            color: #94908b;
            font-weight: bold;
            // font-size: 12px;


            // &:hover {
            //     color: #fc7525;
            // }
        }

    }

}

    }

    .col.third{
        li{
            display: flex;
            padding: 25px 0;

            a{
                color: #94908b;
            }
           div{
            padding-left: 15px;
            color: #94908b;
           }
        }
    }

    .col.fourth{
        img{
            display: inline-block;
            padding: 10px 0;
        }
    }



}



</style>
