<script>
import { store } from './store';

export default {
  data() {
    return {
      store,
      title: 'Ciao',
    };
  },


};
</script>

<template>
  <h1> {{ title }}</h1>
</template>

<style lang="scss">
@use './assets/style/general.scss';
</style>
