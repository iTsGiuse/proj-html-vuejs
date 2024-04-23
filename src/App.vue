<script>
  
  import AppHeader from './components/Header/AppHeader.vue';
  import AppMain from './components/Main/AppMain.vue';

  export default{
    components: {
      AppHeader,
      AppMain
    }
  }

</script>

<template>

  <AppHeader></AppHeader>

  <main>
    <AppMain></AppMain>
  </main>

</template>

<style lang="scss">

  @use './style/generic' as *;


</style>
