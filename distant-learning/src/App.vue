<template>
  <div id="app"> 
    <AppHeader />
    <AppJumbo />
    <AppMain />
    <AppFooter />
  </div>
</template>

<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppJumbo,
    AppMain,
    AppFooter
  }
}
</script>

<style lang="scss">
   @import './assets/style/common.scss';
    @import  './assets/style/variables.scss';
</style>
