<script>

    import HeaderTop from './HeaderTop.vue'

    export default {
        name: 'AppHeader',

        components: {
            HeaderTop,
        }
    }

</script>

<template>
    <header>
        <HeaderTop></HeaderTop>
    </header>   
</template>

<style scoped lang="scss">

    header{
        height: 400px;
    }

</style>
