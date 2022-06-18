<template>
  <div id="app">
    <!-- header -->
    <MyHeader/>
    
    <!-- jumbotron -->
    <MyJumbotron/>
   
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import MyJumbotron from './components/MyJumbotron.vue';
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyJumbotron
}
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}



#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
