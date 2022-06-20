<template>
  <div id="app">
    <!-- header -->
    <MyHeader/>
    
    <!-- jumbotron -->
    <MyJumbotron/>

    <!-- main -->
    <main>
      <!-- foodie journal -->
      <section>
        <FoodieJournal/>
      </section>

      <!-- popular recipes -->
      <section>
        <MyPopularRecipes/>
      </section>

      <!-- culinary collection -->
      <section>
        <CulinaryCollection/>
      </section>
    </main>


    <!-- footer -->
    <MyFooter/>

   
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import MyJumbotron from './components/MyJumbotron.vue';
import FoodieJournal from './components/FoodieJournal.vue';
import MyPopularRecipes from './components/MyPopularRecipes.vue';
import MyFooter from './components/MyFooter.vue';
import CulinaryCollection from './components/CulinaryCollection.vue';




// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyJumbotron,
    MyFooter,
    MyPopularRecipes,
    FoodieJournal,
    CulinaryCollection
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
  background-color: #f5f5f1;
}
</style>
