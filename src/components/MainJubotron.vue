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

<section class="jumbotron"></section>

</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.jumbotron{
    background-image: url(../assets/img/bg-parallax.png);
    background-size: 210%;
    background-position: bottom;
    height: 1050px;
}


</style>