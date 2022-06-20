<template>
  <div id="app">
    <!-- header -->
    <MyHeader/>
    
    <!-- jumbotron -->
    <MyJumbotron/>

    <!-- main -->
    <main>
      <!-- foodie journal -->
      <section></section>

      <!-- popular recipes -->
      <section>
        <MyPopularRecipes/>
      </section>
    </main>


    <!-- footer -->
    <MyFooter/>

   
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import MyJumbotron from './components/MyJumbotron.vue';
import MyFooter from './components/MyFooter.vue';
import MyPopularRecipes from './components/MyPopularRecipes.vue';


// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyJumbotron,
    MyFooter,
    MyPopularRecipes
}
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

ul{
  list-style: none;
}



#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
