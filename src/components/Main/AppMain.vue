<script>

    import InEvidenza from './InEvidenza.vue';
    import ProssimiEventi from './ProssimiEventi.vue';
    import ProssimiEventiCarosello from './ProssimiEventiCarosello.vue';
    import Banner from './Banner.vue';
    import FeaturedPosts from './FeaturedPosts.vue';

    export default {
        name: 'AppMain',

        components:{
            InEvidenza,
            ProssimiEventi,
            ProssimiEventiCarosello,
            Banner,
            FeaturedPosts,
        }
    }

</script>

<template>

    <InEvidenza></InEvidenza>
    <ProssimiEventi></ProssimiEventi>
    <ProssimiEventiCarosello></ProssimiEventiCarosello>
    <Banner></Banner>
    <FeaturedPosts></FeaturedPosts>

</template>

<style scoped lang="scss">



</style>