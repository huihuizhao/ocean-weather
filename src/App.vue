<template>
  <div id="app">
    <my-menu></my-menu>
    <my-map></my-map>
  </div>
</template>

<script>
import myMenu from './components/menu'
import myMap from './components/map'

export default {
  data () {
    return {
      map:null
    }
  },
  components:{
    myMap,
    myMenu
  }
};

</script>

<style>


</style>
