<script>

    import InEvidenza from './InEvidenza.vue';
    import ProssimiEventi from './ProssimiEventi.vue';
    import ProssimiEventiCarosello from './ProssimiEventiCarosello.vue';

    export default {
        name: 'AppMain',

        components:{
            InEvidenza,
            ProssimiEventi,
            ProssimiEventiCarosello,
        }
    }

</script>

<template>

    <InEvidenza></InEvidenza>
    <ProssimiEventi></ProssimiEventi>
    <ProssimiEventiCarosello></ProssimiEventiCarosello>

</template>

<style scoped lang="scss">



</style>