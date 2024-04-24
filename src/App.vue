<script>
  
  import HeaderTop from './components/Header/HeaderTop.vue';
  import HeaderMain from './components/Header/HeaderMain.vue';
  import HeaderFooter from './components/Header/HeaderFooter.vue';
  import InEvidenza from './components/Main/InEvidenza.vue';
  import ProssimiEventi from './components/Main/ProssimiEventi.vue';
  import ProssimiEventiCarosello from './components/Main/ProssimiEventiCarosello.vue';
  import Banner from './components/Main/Banner.vue';
  import FeaturedPosts from './components/Main/FeaturedPosts.vue';
  import Trailer from './components/Main/Trailer.vue';
  import Categorie from './components/Main/Categorie.vue';
  import FooterMain from './components/Footer/FooterMain.vue';
  import Info from './components/Footer/Info.vue';

  export default{
    components: {
      HeaderTop,
      HeaderMain,
      HeaderFooter,
      InEvidenza,
      ProssimiEventi,
      ProssimiEventiCarosello,
      Banner,
      FeaturedPosts,
      Trailer,
      Categorie,
      FooterMain,
      Info
    }
  }

</script>

<template>
  
  <header>
      <HeaderTop></HeaderTop>
      <HeaderMain></HeaderMain>
      <HeaderFooter></HeaderFooter>
  </header>
  <main>
      <InEvidenza></InEvidenza>
      <ProssimiEventi></ProssimiEventi>
      <ProssimiEventiCarosello></ProssimiEventiCarosello>
      <Banner></Banner>
      <FeaturedPosts></FeaturedPosts>
      <Trailer></Trailer>
      <Categorie></Categorie>
  </main>
  <footer>
    <FooterMain></FooterMain>
    <Info></Info>
  </footer>

</template>

<style lang="scss">

  @use './style/generic' as *;


</style>
