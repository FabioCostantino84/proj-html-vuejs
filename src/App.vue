<script>
import { state } from "./state.js";
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

  export default {
    name: 'App',
    data () {
      return{
        state,
      }
    },
    components: {
      AppHeader,
      AppMain,
      AppFooter,
    }
    
  }
</script>

<template>

  <AppHeader></AppHeader>

  <AppMain></AppMain>
  
  <AppFooter></AppFooter>

</template>


<style lang="scss">
// chiedere come farlo funzionare
/* @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap'); */

body{
  font-family: 'Poppins', sans-serif;
}



</style>
