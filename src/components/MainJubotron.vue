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

        <div class="second_img">

            <div class="container h-100 mb-5">
                <div class="row h-100 d-flex justify-content-center align-items-center bg-transparent text-center">
                    <div class="col">
                        <div class="card bg-transparent border-0">

                            <h2>Ready <span class="px-3 py-0"> Team</span></h2>
                            <p class="card-text">No matter whats your company needs, we will be ready to assist you in the best possible way.</p>

                            <div class="bottoni mt-2">
                                <a href="#" class="card-link highlight">GET IN TOUCH</a>
                                <a href="#" class="more card-link">READ MORE</a>
                            </div>
                        </div>

                    </div>
                </div>
            </div>

        </div>

    </section>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;


.jumbotron {
    background-image: url(../assets/svg/sfondo.svg);
    background-size: cover;
    height: 955px;  
    margin: -88px 0 0;
}
.second_img {
    background-repeat: no-repeat;
    background-image: url(../assets/img/bg-parallax.png);
    background-size: 210%;
    background-position: center;
    height: 955px;
}

.container{
    width: 35%;
}

h2{
    font-weight: 900;
    font-size: 75px;
    color: $SB_blu;
}

span{
    color: $SB_verdeacqua_1;
    background-color: $SB_verdeacqua_2_tras;
    border-radius: 5px;

    
}

p{
    color: $SB_grigioscuro;
    font-size: 20px;
    padding: 25px 67px;
}
a {
    text-decoration: none;
    color: $SB_grigioscuro;
    font-size: large;
    font-weight: 500;
    padding: 10px 20px;
    border: 1px solid;
    border-color: $SB_verdeacqua_1;

}

a:hover, .highlight{
    background-color: $SB_verdeacqua_1;
    color: $SB_grigiochiaro;
    border-radius: 5px;
    padding: 10px 25px;
    font-size: 20px;
}
.more{
    text-decoration: none;
    color: $SB_verdeacqua_1;
    font-size: large;
    font-weight: 500;
    font-size: 20px;
    padding: 10px 25px;
    border: 1px solid;
    border-radius: 5px;
    border-color: $SB_verdeacqua_1;
}
</style>