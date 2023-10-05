<script>
export default {
    name: 'MainCompany',
    data() {
        return {

        }
    },
}
</script>

<template>
    <div class="container-fluid d-flex p-0">
        <div class="left_container container-fluid">
            <div class="container text-white">
                <div class="row">
                    <div class="col">
                        <div class="card bg-transparent border-0">
                            <div class="card-body px-2 header_card">
                                ABOUT THE NETWORK
                            </div>
                            <div class="card-body px-2">
                                <h3 class="card-title"><span class="px-3">The</span> Company</h3>
                                <p class="card-text py-3">For 12 years we have been providing audit and warranty, financial advice, risk advice, taxes and related services to select clients..</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="row">
                    <div class="my_col col-6 ps-4">
                        <div class="card border-0 bg-transparent d-flex">
                            <div class="icon d-flex align-items-baseline">
                                <i class="fa-regular fa-pen-to-square me-2"></i>
                                <h6>Tradition</h6>
                            </div>
                            <p class="pt-3 card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>

                    <div class="my_col col-6 ps-4">
                        <div class="card border-0 bg-transparent d-flex">
                            <div class="icon d-flex align-items-baseline">
                                <i class="fa-regular fa-pen-to-square me-2"></i>
                                <h6>Security</h6>
                            </div>
                            <p class="pt-3 card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>

                    <div class="my_col col-6 ps-4 pb-3">
                        <div class="card border-0 bg-transparent d-flex">
                            <div class="icon d-flex align-items-baseline">
                                <i class="fa-regular fa-pen-to-square me-2"></i>
                                <h6>Certificate</h6>
                            </div>
                            <p class="pt-3 card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>

                    <div class="my_col col-6 ps-4 pb-3">
                        <div class="card border-0 bg-transparent d-flex">
                            <div class="icon d-flex align-items-baseline">
                                <i class="fa-regular fa-pen-to-square me-2"></i>
                                <h6>Expertise</h6>
                            </div>
                            <p class="pt-3 card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>
                </div>

                <div class="my_button px-2">
                    <a href="#" class="card-link highlight">GET IN TOUCH</a>
                    <a href="#" class="more card-link mx-4">READ MORE</a>
                </div>
            </div>
        </div>

        <div class="container-fluid bg_img"></div>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.left_container {
    background-color: $SB_blu;
    height: 930px;
    width: 100%;
}

.container{
    width: 70%;
    margin-right: -50px;
}

.bg_img {
    background-image: url(../assets/img/about-4.jpg);
    height: 930px;
    width: 100%;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}

.header_card {
    color: $SB_verdeacqua_1;
    font-weight: 700;
    padding-top: 100px;
}

h3 {
    font-weight: 900;
    font-size: 50px;
    color: $SB_grigiochiaro;
}

span {
    color: $SB_grigiochiaro;
    background-color: $SB_verdeacqua_2_tras;
    border-radius: 5px;


}

p {
    color: $SB_grigioscuro;
    font-size: 18px;
}

.btn {
    background-color: $SB_verdeacqua_1;
    color: $SB_grigiochiaro;
    border: 1px solid;
    border-radius: 5px;
    border-color: $SB_verdeacqua_1;
    padding: 8px 30px;
    font-size: 20px;
}

.see_all {
    padding-right: 10px;
    padding-bottom: 50px;
}

.my_col{
    margin-right: -40px;
}

.card {
    height: 100%;
    padding-top: 28px;
    padding-bottom: 30px;
}

img {
    width: 16%;
    fill: $SB_verdeacqua_1;
}

i {
    color: $SB_verdeacqua_2;
    font-size: 25px;
}

h6 {
    color: $SB_grigiochiaro;
    font-weight: 700;
    font-size: 25px;
}

.my_button{
    padding-top: 30px;
    padding-bottom: 50px;
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

a:hover,
.highlight {
    background-color: $SB_verdeacqua_1;
    color: $SB_grigiochiaro;
    border-radius: 5px;
    padding: 10px 25px;
    font-size: 20px;
}

.more {
    text-decoration: none;
    color: $SB_grigiochiaro;
    font-size: large;
    font-weight: 500;
    font-size: 20px;
    padding: 10px 25px;
    border: 1px solid;
    border-radius: 5px;
    border-color: $SB_verdeacqua_1;
}
</style>