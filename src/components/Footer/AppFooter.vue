<script>
    
    import FooterMain from './FooterMain.vue';
    import Info from './Info.vue';

    export default {
        name: 'AppFooter',

        components:{
            FooterMain,
            Info
        }
    }

</script>

<template>

    <FooterMain></FooterMain>
    <Info></Info>

</template>

<style scoped lang="scss">

    @use '../../style/partials/variables' as *;



</style>