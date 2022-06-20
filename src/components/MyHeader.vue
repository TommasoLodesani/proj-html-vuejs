<template>
    <header>

        <div class="header-top">
            <div class="left">
                Download App <span> iOS</span> Advertise with us
            </div>
            <div class="right">
                <a href="#"><font-awesome-icon icon="fa-brands fa-twitter" /></a>
                <a href="#"><font-awesome-icon icon="fa-brands fa-twitter" /></a>
                <a href="#"><font-awesome-icon icon="fa-brands fa-twitter" /></a>
                <a href="#"><font-awesome-icon icon="fa-brands fa-twitter" /></a>
            </div>
        </div>

        <div class="container-img">
            <img src="../assets/img/avada-food-logo.png" alt="">

        </div>
    
      <nav>
        <ul>
          <li v-for="(link, inedx) in links" :key="inedx">
            <a href="link.url" :class="link.current ? 'here' : '' "> {{link.text}}</a>
          </li>          
        </ul>
      </nav>

      

    </header>
  
</template>

<script>
export default {
  name: 'MyHeader',
  data(){
    return {
      links :[
        {
          text : "Home",
          url : "#",
          current : false
        },
        {
          text : "Recipes",
          url : "#",
          current : true
        },
        {
          text : "Places",
          url : "#",
          current : false
        },
        {
          text : "Blog",
          url : "#",
          current : false
        },
        {
          text : "Abou",
          url : "#",
          current : false
        },
        {
          text : "Contact",
          url : "#",
          current : false
        },
        {
          text : "Search",
          url : "#",
          current : false
        },
      ]
    }
  }
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

header{
  background-color: #ffffff;
}
.header-top{
    width: 62%;
    margin: auto;
    padding-top: 20px;
    padding-bottom: 15px;
    font-size: 12px;
    color: #847f7a;
    display: flex;
    justify-content: space-between;

    .left{
        span{
            font-size: 10px;
            background-color: #fc7525;
            color: white;
            border-radius: 15%;
            padding: 2px;
            margin-right: 20px;
        }

    }


    .right{
        font-size: 15px;
        a{
          color: #847f7a;
          padding: 0 15px;
        }

    }



}

.container-img{
    display: flex;
    justify-content: center;
}

nav{
  
  padding: 30px 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  justify-content: center;


  ul{
    list-style-type: none;

    li{
      display: inline-block;
      padding: 0 35px;

      a{
        text-decoration: none;
        color: black;
        // font-size: 12px;
       

        &:hover{
          color: #fc7525;
        }
        &.here{
          border-bottom: solid 4px #fc7525;
          padding-bottom: 13px;
          color: #fc7525;
        }
      }

    }
    
  }

}
    

</style>
