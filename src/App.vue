<template>
  <div class="index">
    <MenuPrincipal />
    <Home />
    <Sobre />
  </div>
</template>

<script>
import MenuPrincipal from './components/menuprincipal.vue'
import Home from './components/home.vue'
import Sobre from './components/sobre.vue'

export default {
  name: 'App',
  components: {
    MenuPrincipal,
    Home,
    Sobre
  }
}

$(document).ready(function () {
  //MENU MOBILE
  $(".sidenav").sidenav();
  //LINK INTERNO
  $(".scrollspy").scrollSpy({
    scrollOffset: 0
  });
});
</script>

<style>
#app {
  height: 100%;
}


.index {
  height: 100%;
  width: 100%;
}

.row {
  margin-bottom: 0;
}

.tabs {
  background-color: #222;
}

.tabs .tab a {
  color: #fff;
}

.tabs .tab a:hover,
.tabs .tab a:active {
  color: #2dc7d0;
}

.tabs .indicator {
  background-color: #2dc7d0;
}

@media only screen and (max-width: 480px) {
  .container {
    width: 80%;
  }

  .carousel-item img {
    max-width: 100%;
    height: auto;
  }

  .card-image-horizontal {
    display: none;
  }
}

@media only screen and (min-width: 601px) {
  .banner {
    padding-top: 4.5rem;
  }

  .banner h2 {
    font-size: 4rem;
  }

  .container {
    width: 85%;
  }

  .carousel-item img {
    max-width: 100%;
    height: auto;
  }
}

@media only screen and (min-width: 993px) {
  .banner {
    padding-top: 5rem;
  }

  .banner h2 {
    font-size: 4rem;
  }

  .container {
    width: 90%;
  }

  .carousel-item img {
    max-width: 100%;
    height: auto;
  }
}</style>