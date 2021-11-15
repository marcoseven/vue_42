<template>
    <header id="site_header">
      <Logo/>
      <!-- /.logo -->
      <nav class="main_menu">
        <a href="">Home</a>
        <a href="" class="active">Prodotti</a>
        <a href="">Chi siamo</a>
        <a href="">Contatti</a>
      </nav>
      <!-- /.main_menu --> 
    </header>
</template>

<script>
import Logo from './Logo.vue';
export default {
  /* Options object */
  
  components: {
    Logo
  }
}
</script>

<style lang="scss">
#site_header {
  text-align: center;
  .main_menu {
    margin: 1.5rem 0;
    a {
      padding: 1rem;
      text-decoration: none;
      color: #333;
      &.active {
        background: #d0e6f9;

      }
      &:hover {
        text-decoration: underline;
      }
    }
  }

}

</style>