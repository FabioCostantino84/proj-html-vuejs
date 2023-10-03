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


<style lang="scss" scoped>

</style>
