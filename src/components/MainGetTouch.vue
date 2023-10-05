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
            <div class="col-8">
                <div class="card bg-transparent border-0">
                    <div class="card-body px-2 header_card">
                        ABOUT THE NETWORK
                    </div>
                    <div class="card-body px-2">
                        <h3 class="card-title">Get in <span class="px-3">Touch</span></h3>
                        <p class="card-text py-3">We will responsed to your message as soon as possible.</p>
                    </div>
                </div>

                <div class="d-flex p-2">
                    <input type="text" class="form-control p-3 mx-2" placeholder="Name" aria-label="Name">
                    <input type="email" class="form-control p-3 mx-2" placeholder="Email" aria-label="Email">
                </div>

                <div class="d-flex p-2">
                    <input type="text" class="form-control p-3 mx-2" placeholder="Phone" aria-label="Phone">
                    <!-- <input type="text" class="form-control p-3 mx-2" placeholder="More info" aria-label="More Info"> -->


                    <select class="form-select p-3 mx-2" name="" id="">
                        <option class="" selected>More Info</option>
                        <option value="">New Delhi</option>
                        <option value="">Istanbul</option>
                        <option value="">Jakarta</option>
                    </select>

                </div>

                <div class="form-floating p-2">
                    <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2"
                        style="height: 200px"></textarea>
                    <label for="floatingTextarea2">Message</label>
                </div>

            </div>
            <div class="col-4"></div>
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

input, select {
    background-color: $SB_grigio;
    border-radius: 5px;
}
</style>