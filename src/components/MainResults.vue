<script>
export default {
    name: 'MainResults',
    data() {
        return {

        }
    },
}
</script>

<template>
    <div id="bg_results">
        <div class="container">
            <div class="row">
                <div class="col-12 pt-5 d-flex justify-content-center">
                    <div class="card bg-transparent border-0">
                        <div class="card-body header_card text-center">
                            WHAT ARE WE DOING
                        </div>
                        <div class="card-body">
                            <h3 class="card-title"><span class="px-3 py-0">Results</span> in Numbers</h3>
                        </div>
                    </div>
                </div>
                <!-- / title results -->


                <div class="col-3">
                    <div class="card-body text-center">
                        <h5 class="card-title pb-3">128</h5>
                        <h6 class="card-subtitle mb-2">Certifications</h6>
                    </div>
                </div>

                <div class="col-3">
                    <div class="card-body text-center">
                        <h5 class="card-title pb-3">230</h5>
                        <h6 class="card-subtitle mb-2">Employees</h6>
                    </div>
                </div>

                <div class="col-3">
                    <div class="card-body text-center">
                        <h5 class="card-title pb-3">517</h5>
                        <h6 class="card-subtitle mb-2">Customers</h6>
                    </div>
                </div>

                <div class="col-3">
                    <div class="card-body text-center">
                        <h5 class="card-title pb-3">94</h5>
                        <h6 class="card-subtitle mb-2">Country Served</h6>
                    </div>
                </div>
                <!-- / cards results -->

            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.container {
    width: 60%;
}

#bg_results {
    background-image: url(../assets/img/bg-7.jpg);
    height: 615px;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

h3 {
    font-weight: 900;
    font-size: 45px;
    color: $SB_grigiochiaro;
}

span {
    color: $SB_grigiochiaro;
    background-color: $SB_verdeacqua_2_tras;
    border-radius: 5px;


}

.header_card {
    color: $SB_verdeacqua_2;
    font-weight: 700;
    padding-top: 100px;
    font-size: 15px;
}


h5 {
    font-weight: 700;
    font-size: 40px;
    color: $SB_verdeacqua_2;
    padding-top: 70px;
}

h6 {
    font-weight: 600;
    font-size: 25px;
    color: $SB_grigiochiaro;


}
</style>