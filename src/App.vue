<script>
  
  import AppHeader from './components/Header/AppHeader.vue';
  import AppMain from './components/Main/AppMain.vue';
  import AppFooter from './components/Footer/AppFooter.vue';

  export default{
    components: {
      AppHeader,
      AppMain,
      AppFooter
    }
  }

</script>

<template>

  <AppHeader></AppHeader>

  <main>
    <AppMain></AppMain>
  </main>

  <footer>
    <AppFooter></AppFooter>
  </footer>

</template>

<style lang="scss">

  @use './style/generic' as *;


</style>
