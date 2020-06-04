<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <TopNav/>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue';
import TopNav     from '@/components/TopNav.vue';
export default {
  name: 'App',
  components: {
    HelloWorld,
    TopNav
  }
}
</script>
<style lang="sass" scoped>
    @import '@/assets/scss/_utilities';
</style>
