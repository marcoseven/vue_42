<template>
  <div id="app">
  <section>
      <SectionTitle/>
    </section>
    <ListElements/>
   
   <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld/> -->
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import ListElements from './components/ListElements.vue'
import SectionTitle from './components/SectionTitle.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld
    ListElements,
    SectionTitle
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
