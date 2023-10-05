<script>
export default {
    name: 'MainGetTouch',
    data() {
        return {

        }
    },
}
</script>

<template>
    <div class="container">

        <div class="row">
            <div class="col-9">
                <div class="card bg-transparent border-0">
                    <div class="card-body px-2 header_card">
                        ABOUT THE NETWORK
                    </div>
                    <div class="card-body px-2">
                        <h3 class="card-title">Get in <span class="px-3">Touch</span></h3>
                        <p class="card-text py-3">We will responsed to your message as soon as possible.</p>
                    </div>
                </div>
            </div>
            <div class="col-3"></div>
        </div>

    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.container {
    width: 65%;
}

.header_card {
    color: $SB_verdeacqua_2;
    font-weight: 700;
    padding-top: 100px;
}

h3 {
    font-weight: 900;
    font-size: 50px;
    color: $SB_blu;
}

span {
    color: $SB_verdeacqua_2;
    background-color: $SB_verdeacqua_2_tras;
    border-radius: 5px;
}

p {
    color: $SB_grigioscuro;
    font-size: 18px;
}
</style>