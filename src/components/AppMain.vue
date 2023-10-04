<script>
import MainJubotron from './MainJubotron.vue'
import MainServices from './MainServices.vue'
export default {
    name: 'AppMain',
    data() {
        return {
            
        }
    },
    components:{
        MainJubotron, 
        MainServices       
    }

}
</script>

<template>
    
    <MainJubotron></MainJubotron>

    <MainServices></MainServices>

</template>


<style lang="scss" scoped>

</style>