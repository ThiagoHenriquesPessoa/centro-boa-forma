<template>
  <div class="index">
    <MenuPrincipal/>
    <Home/>
  </div>  
</template>

<script>
import MenuPrincipal from './components/menuprincipal.vue'
import Home from './components/home.vue'

export default {
  name: 'App',
  components: {
    MenuPrincipal,
    Home    
  }
}
</script>

<style>
  #app {
    height: 100%;
  }

  
.index {
 height: 100%;
 width: 100%;
}
</style>