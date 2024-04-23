<script>

    import HeaderTop from './HeaderTop.vue';
    import HeaderMain from './HeaderMain.vue';
    import HeaderFooter from './HeaderFooter.vue';

    export default {
        name: 'AppHeader',

        components: {
            HeaderTop,
            HeaderMain,
            HeaderFooter
        }
    }

</script>

<template>
    <header>
        <HeaderTop></HeaderTop>
        <HeaderMain></HeaderMain>
        <HeaderFooter></HeaderFooter>
    </header>   
</template>

<style scoped lang="scss">

    header{
        height: 200px;
    }

</style>
