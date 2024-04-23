<script>

    import HeaderTop from './HeaderTop.vue';
    import HeaderMain from './HeaderMain.vue';

    export default {
        name: 'AppHeader',

        components: {
            HeaderTop,
            HeaderMain
        }
    }

</script>

<template>
    <header>
        <HeaderTop></HeaderTop>
        <HeaderMain></HeaderMain>
    </header>   
</template>

<style scoped lang="scss">

    header{
        height: 400px;
    }

</style>
