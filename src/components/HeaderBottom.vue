<script>
export default {
    name: 'HeaderBottom',
    data() {
        return {

        }
    }

}
</script>
        
<template>
    <div class="container bg-transparent">
        <div class="row">
            <div class="col-4">
                <img src="../assets/img/logo.PNG" class="" alt="">
            </div>
            <div class="col-8">
                <nav class="nav d-flex justify-content-around align-items-center p-3">
                    <a class="nav-link" href="#">HOME</a>
                    <a class="nav-link" href="#">SERVICES</a>
                    <a class="nav-link" href="#">ABOUT</a>
                    <a class="nav-link" href="#">PROJECTS</a>
                    <a class="nav-link" href="#">RESULTS</a>
                    <a class="nav-link highlight" href="#">GET IN TOUCH</a>
                </nav>
            </div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.container{
    position: relative;
    top: 10px

}

img {
    padding: 15px 40px 15px 15px;
    width: 50%;
}

a {
    color: $SB_grigioscuro;
    font-size: large;
    font-weight: 500;
    padding: 10px 20px;

}

a:hover, .highlight{
    background-color: $SB_verdeacqua_1;
    color: $SB_grigiochiaro;
    border-radius: 5px;


}
</style>