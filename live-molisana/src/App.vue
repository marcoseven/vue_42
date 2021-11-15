<template>
  <div id="app">

    <SiteHeader />
    <!-- /#site_header -->
   
    <MainContent />
    <!-- /#site_main -->
   
    <SiteFooter />
    <!-- /#site_footer -->
  
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";
import MainContent from "./components/MainContent.vue";
import SiteFooter from "./components/SiteFooter.vue";

//import Logo from "./components/Logo.vue"; // Spostare nel componente footer


export default {
  name: "App",
  components: {
    SiteHeader,
    MainContent,
    SiteFooter
  },
};
</script>

<style lang="scss">
@import './assets/scss/variables.scss';
@import './assets/scss/common.scss';
</style>
