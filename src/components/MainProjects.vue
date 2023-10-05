<script>
export default {
    name: 'MainProjects',
    data() {
        return {

        }
    },
}
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-12 d-flex justify-content-center">
                <div class="card bg-transparent border-0">
                    <div class="card-body header_card text-center">
                        WE DO MORE FOR EVERYONE
                    </div>
                    <div class="card-body">
                        <h3 class="card-title">Actions & <span class="px-3 py-0">Projects</span></h3>
                    </div>
                </div>
            </div>
            <div class="col"></div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

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
</style>