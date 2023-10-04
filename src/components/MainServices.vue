<script>
export default {
    name: 'MainServices',
    data() {
        return {

        }
    },
}
</script>

<template>
    <section class="services">
        <div class="container">
            <div class="row">
                <div class="col-10">
                    <div class="card bg-transparent border-0">
                        <div class="card-body header_card">
                            OUR BUSINESS AREA
                        </div>
                        <div class="card-body">
                            <h3 class="card-title">Exellence in <span class="px-3 py-0">Services</span></h3>
                            <p class="card-text">We are leaders in providing consultancy services with a set of cutting-edge
                                technologies and a team of experienced and renowned professionals. These are some options
                                that you can hire.</p>
                        </div>
                    </div>
                </div>
                <div class="col-2 d-flex justify-content-end align-items-end">
                    <div class="see_all">
                        <a class="btn" href="#" role="button">SEE ALL</a>
                    </div>
                </div>
            </div>

            <div class="row">
                <div class="col-4 px-4 py-4">
                    <div class="card border-0">
                        <div class="container px-5 d-flex justify-content-between pt-5 pb-2">
                            <img src="../assets/svg/svg-1.svg" class="card-img-top" alt="svg">
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>

                        <div class="container text-start px-5 card-body">
                            <h5>Audit & Assurance</h5>
                            <p class="pt-3 card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>
                </div>
                <!-- /first card -->

                <div class="col-4 px-4 py-4">
                    <div class="card border-0">
                        <div class="container px-5 d-flex justify-content-between pt-5 pb-2">
                            <img src="../assets/svg/svg-2.svg" class="card-img-top" alt="svg">
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>

                        <div class="container text-start px-5 card-body">
                            <h5>Finacial Advisory</h5>
                            <p class="pt-3 card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>
                </div>

                <div class="col-4 px-4 py-4">
                    <div class="card border-0">
                        <div class="container px-5 d-flex justify-content-between pt-5 pb-2">
                            <img src="../assets/svg/svg-3.svg" class="card-img-top" alt="svg">
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>

                        <div class="container text-start px-5 card-body">
                            <h5>Analytics and M&A</h5>
                            <p class="pt-3 card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>
                </div>

                <div class="col-4 px-4 py-4">
                    <div class="card border-0">
                        <div class="container px-5 d-flex justify-content-between pt-5 pb-2">
                            <img src="../assets/svg/svg-4.svg" class="card-img-top" alt="svg">
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>

                        <div class="container text-start px-5 card-body">
                            <h5>Middle Marketing</h5>
                            <p class="pt-3 card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>
                </div>

                <div class="col-4 px-4 py-4">
                    <div class="card border-0">
                        <div class="container px-5 d-flex justify-content-between pt-5 pb-2">
                            <img src="../assets/svg/svg-5.svg" class="card-img-top" alt="svg">
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>

                        <div class="container text-start px-5 card-body">
                            <h5>Legal Consulting</h5>
                            <p class="pt-3 card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>
                </div>

                <div class="col-4 px-4 py-4">
                    <div class="card border-0">
                        <div class="container px-5 d-flex justify-content-between pt-5 pb-2">
                            <img src="../assets/svg/svg-6.svg" class="card-img-top" alt="svg">
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>

                        <div class="container text-start px-5 card-body">
                            <h5>Regulatory Risk</h5>
                            <p class="pt-3 card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </section>
    <!-- /end sevices -->
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.services {
    background-color: $SB_celestechiaro;
}

.header_card {
    color: $SB_verdeacqua_1;
    font-weight: 700;
    padding-top: 100px;
}

h3 {
    font-weight: 900;
    font-size: 53px;
    color: $SB_blu;
}

span {
    color: $SB_verdeacqua_1;
    background-color: $SB_verdeacqua_2_tras;
    border-radius: 5px;


}

p {
    color: $SB_grigioscuro;
    font-size: 18px;
    padding-top: 40px;
    padding-bottom: 40px;
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

.see_all{
    padding-right: 10px;
    padding-bottom: 50px;
}

.card {
    border-radius: 10px;
    height: 100%;
}

img {
    width: 16%;
    fill: $SB_verdeacqua_1;
}

i {
    color: $SB_verdeacqua_2;
    font-size: 30px;
}

h5 {
    color: $SB_blu;
    font-weight: 700;
    font-size: 28px;
}
</style>