<template>
  <div class="index">
    <Home/>
  </div>  
</template>

<script>
import Home from './components/home.vue'

export default {
  name: 'App',
  components: {
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