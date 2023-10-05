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
                        <h5 class="card-title">128</h5>
                        <h6 class="card-subtitle mb-2">Certifications</h6>
                    </div>

                </div>

                <div class="col-3">

                </div>

                <div class="col-3">

                </div>

                <div class="col-3">

                </div>
                <!-- / cards results -->
            </div>
        </div>

    </div>

    <h1>ciao</h1>
    <h1>ciao</h1>
    <h1>ciao</h1>
    <h1>ciao</h1>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

#bg_results {
    background-image: url(../assets/img/bg-7.jpg);
    height: 630px;
    background-position: center;
}

h3 {
    font-weight: 900;
    font-size: 53px;
    color: $SB_grigiochiaro;
}

span {
    color: $SB_grigiochiaro;
    background-color: $SB_verdeacqua_2_tras;
    border-radius: 5px;


}

.header_card {
    color: $SB_verdeacqua_1;
    font-weight: 700;
    padding-top: 100px;
}


h5{
    font-weight: 600;
    font-size: 25px;
    color: $SB_verdeacqua_1;
}

h6{
    font-weight: 600;
    font-size: 25px;
    color: $SB_grigiochiaro;
    

}
/*a {
    color: $SB_grigioscuro;
    font-size: large;
    font-weight: 500;
    padding: 11px 15px;

}

a:hover,
.highlight {
    background-color: $SB_verdeacqua_2_tras;
    color: $SB_grigioscuro;
    border-radius: 5px;
}

.card{
    color: $SB_grigiochiaro;
    border-radius: 10px;
}

img{
    filter: brightness(0.5);
    border-radius: 15px;

}


.row{
    padding-bottom: 150px;
} */
</style>