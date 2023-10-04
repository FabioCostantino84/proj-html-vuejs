<script>
export default {
    name: 'MainJumbotron',
    data() {
        return {
            
        }
    },
}
</script>

<template>

<section class="jumbotron">

    <div class="second_img bg_img_1">
        
    </div>

</section>

</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.second_img{
    background-repeat: no-repeat;
    background-image: url(../assets/img/bg-parallax.png); 
    background-size: 210%;
    background-position: bottom;
    height: 1050px;
}
.jumbotron{
    background-image: url(../assets/svg/sfondo.svg); 
    background-size: cover;
    height: 1050px;
}


</style>