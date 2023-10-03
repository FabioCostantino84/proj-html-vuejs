<script>
export default {
    name: 'HeaderTop',
    data() {
        return {

        }
    }

}
</script>
        
<template>

    <div id="header_top">
        <div class="container w-75">
            <div class="row p-3">
                <div class="col-6"><i class="fa-solid fa-clock"></i> Open Hours: Mon - Sat - 9:00 - 18:00 </div>
                <div class="col-6 d-flex justify-content-around"> 
                    <div><i class="fa-solid fa-phone"></i> +1 (305) 1234-5678</div>
                    <div><i class="fa-solid fa-envelope"></i> hello@exeple.com</div>
                    <div><i class="fa-brands fa-facebook-f"></i></div>
                    <div><i class="fa-brands fa-twitter"></i></div>
                    <div><i class="fa-brands fa-linkedin-in"></i></div>
                </div>
            </div>
        </div>

    </div>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

#header_top, .card {
    background-color: $SB_blu;
    color: $SB_grigioscuro;
    border: 0;
}
</style>