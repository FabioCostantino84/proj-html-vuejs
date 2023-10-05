<script>
export default {
    name: 'MainIcon',
    data() {
        return {

        }
    },
}
</script>

<template>
    <div id="icon">
        <div class="container h-100">
            <div class="row h-100">
                <div class="col d-flex align-items-center justify-content-around align-content-center">
                    <img style="width: 95px;" src="../assets/img/logo-4.png" alt="">
                    <img style="width: 60px;" src="../assets/img/logo-5.png" alt="">
                    <img style="width: 140px;" src="../assets/img/logo-1.png" alt="">
                    <img style="width: 130px;" src="../assets/img/logo-2.png" alt="">
                    <img style="width: 100px;" src="../assets/img/logo-3.png" alt="">
                    <img style="width: 95px;" src="../assets/img/logo-4.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

#icon {
    background-color: $SB_blu;
    height: 290px;
}

.container {
    width: 60%;
}

img {
    width: 90px;
}
</style>