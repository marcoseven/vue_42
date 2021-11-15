<template>
   <footer id="site_footer">
      <div class="container">
        <div class="row">
          <div class="col-4">
            <Logo/>
          </div>
           <div class="col-4">
            <h3>Panificio</h3>
            <ul>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
            </ul>
          </div>
           <div class="col-4">
            <h3>Prodotti</h3>
           <ul>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
            </ul>
          </div>
        </div>
      </div>

    </footer>
</template>

<script>
import Logo from './Logo.vue';
export default {
  components: {
    Logo
  }
}
</script>

<style lang="scss">
// molisana_primary_color
@import '../assets/scss/variables.scss';

#site_footer {
  height: 400px;
  padding-top: 2rem;
  background-image: url('../assets/footer-montagne-bottom.jpg');
  background-position-y: bottom;
  background-repeat: no-repeat;



  h3 {
    color: $molisana_primary_color;
    margin-bottom: 1.5rem;
  }

  ul {
    list-style: none;
    a {
      text-decoration: none;
      color: #333;
    }
  }
}

</style>
