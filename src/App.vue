<template>
  <div id="app">
    <TopNav/>
  </div>
</template>

<script>
import Vue from 'vue'
import { BootstrapVue, IconsPlugin } from 'bootstrap-vue';
Vue.use(BootstrapVue);
Vue.use(IconsPlugin);
import '@/assets/scss/bootstrap.scss';
import TopNav     from '@/components/TopNav.vue';
export default {
  name: 'App',
  components: {
    TopNav
  }
}
</script>
<style lang="sass" scoped>
</style>
