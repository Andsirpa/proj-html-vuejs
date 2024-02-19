<script>
import { store } from './store';
import { AppHeader } from "./components/AppHeader.vue";
import { AppMain } from "./components/AppMain.vue";
import { AppFooter } from "./components/AppFooter.vue";
export default {
  data() {
    return {
      store,
      title: 'Ciao',
    };
  },

  components: { AppHeader, AppMain, AppFooter }

};
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss">
@use './assets/style/general.scss';
</style>
