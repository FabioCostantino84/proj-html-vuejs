<script>
import HeaderTop from './HeaderTop.vue';
import HeaderBottom from './HeaderBottom.vue';

export default {
    name: 'AppHeader',
    data() {
        return {
            
        }
    },
    components: {
        HeaderTop,
        HeaderBottom,
    }

}
</script>

<template>

    <HeaderTop></HeaderTop>

    <HeaderBottom></HeaderBottom>

</template>


<style lang="scss" scoped>

</style>