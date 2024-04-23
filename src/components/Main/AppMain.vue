<script>

    import InEvidenza from './InEvidenza.vue';
    import ProssimiEventi from './ProssimiEventi.vue';
    import ProssimiEventiCarosello from './ProssimiEventiCarosello.vue';
    import Banner from './Banner.vue';

    export default {
        name: 'AppMain',

        components:{
            InEvidenza,
            ProssimiEventi,
            ProssimiEventiCarosello,
            Banner,
        }
    }

</script>

<template>

    <InEvidenza></InEvidenza>
    <ProssimiEventi></ProssimiEventi>
    <ProssimiEventiCarosello></ProssimiEventiCarosello>
    <Banner></Banner>

</template>

<style scoped lang="scss">



</style>