<script>
import MainJubotron from './MainJubotron.vue'
import MainServices from './MainServices.vue'
import MainCompany from './MainCompany.vue'
export default {
    name: 'AppMain',
    data() {
        return {
            
        }
    },
    components:{
        MainJubotron, 
        MainServices,
        MainCompany,     
    }

}
</script>

<template>
    
    <MainJubotron></MainJubotron>

    <MainServices></MainServices>

    <MainCompany></MainCompany>

</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

</style>