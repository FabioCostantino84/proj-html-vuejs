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
            <div class="col-12 pt-5 d-flex justify-content-center">
                <div class="card bg-transparent border-0">
                    <div class="card-body header_card text-center">
                        WE DO MORE FOR EVERYONE
                    </div>
                    <div class="card-body">
                        <h3 class="card-title">Actions & <span class="px-3 py-0">Projects</span></h3>
                    </div>
                </div>
            </div>
            <!-- / title project -->

            <div class="col-12 w-75 m-auto pt-3">
                <nav class="nav d-flex justify-content-around align-items-center p-3">
                    <a class="nav-link highlight" href="#">ALL</a>
                    <a class="nav-link" href="#">INSTITUTIONAL</a>
                    <a class="nav-link" href="#">SOCIAL</a>
                    <a class="nav-link" href="#">EVENTS</a>
                    <a class="nav-link" href="#">INNOVATION</a>
                    <a class="nav-link" href="#">ENVIRONMENT</a>
                    <a class="nav-link" href="#">TECHNOLOGY</a>
                </nav>
            </div>
            <!-- / nav projects -->

            <div class="col-4">
                <div class="card border-0 py-4">
                    <img src="../assets/img/project-1.jpg" class="card-img" alt="...">
                    <div class="card-img-overlay text-center">
                        <h5 class="card-title px-4">Academic professional program in social media</h5>
                    </div>
                </div>
            </div>

            <div class="col-4">
                <div class="card border-0 py-4">
                    <img src="../assets/img/project-2.jpg" class="card-img" alt="...">
                    <div class="card-img-overlay text-center">
                        <h5 class="card-title px-5">President's speech at the annual meeting</h5>
                    </div>
                </div>
            </div>

            <div class="col-4">
                <div class="card border-0 py-4">
                    <img src="../assets/img/project-3.jpg" class="card-img" alt="...">
                    <div class="card-img-overlay text-center">
                        <h5 class="card-title px-5">International business trip in Shanghai</h5>
                    </div>
                </div>
            </div>

            <div class="col-4">
                <div class="card border-0 py-4">
                    <img src="../assets/img/project-4.jpg" class="card-img" alt="...">
                    <div class="card-img-overlay text-center">
                        <h5 class="card-title px-5">Technology workshop with education theme</h5>
                    </div>
                </div>
            </div>

            <div class="col-4">
                <div class="card border-0 py-4">
                    <img src="../assets/img/project-5.jpg" class="card-img" alt="...">
                    <div class="card-img-overlay text-center">
                        <h5 class="card-title px-4">Donation of clothes and food to the partner NGO</h5>
                    </div>
                </div>
            </div>

            <div class="col-4">
                <div class="card border-0 py-4">
                    <img src="../assets/img/project-6.jpg" class="card-img" alt="...">
                    <div class="card-img-overlay text-center">
                        <h5 class="card-title px-4">Confraternization of the procurement team</h5>
                    </div>
                </div>
            </div>
            <!-- / cards projects -->
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

a {
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

h5{
    font-weight: 600;
    font-size: 25px;
    padding-top: 305px;
}

.row{
    padding-bottom: 150px;
}
</style>