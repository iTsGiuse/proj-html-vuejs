<script>

    import InEvidenza from './InEvidenza.vue';
    import ProssimiEventi from './ProssimiEventi.vue';
    import ProssimiEventiCarosello from './ProssimiEventiCarosello.vue';
    import Banner from './Banner.vue';
    import FeaturedPosts from './FeaturedPosts.vue';
    import Trailer from './Trailer.vue';
    import Categorie from './Categorie.vue';

    export default {
        name: 'AppMain',

        components:{
            InEvidenza,
            ProssimiEventi,
            ProssimiEventiCarosello,
            Banner,
            FeaturedPosts,
            Trailer,
            Categorie
        }
    }

</script>

<template>

    <InEvidenza></InEvidenza>
    <ProssimiEventi></ProssimiEventi>
    <ProssimiEventiCarosello></ProssimiEventiCarosello>
    <Banner></Banner>
    <FeaturedPosts></FeaturedPosts>
    <Trailer></Trailer>
    <Categorie></Categorie>

</template>

<style scoped lang="scss">



</style>