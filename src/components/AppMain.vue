<script>
import MainJubotron from './MainJubotron.vue'
import MainServices from './MainServices.vue'
import MainCompany from './MainCompany.vue'
import MainProjects from './MainProjects.vue'
import MainResults from './MainResults.vue'
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
        MainProjects,
        MainResults,    
    }

}
</script>

<template>
    
    <MainJubotron></MainJubotron>

    <MainServices></MainServices>

    <MainCompany></MainCompany>

    <MainProjects></MainProjects>

    <MainResults></MainResults>

</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

</style>