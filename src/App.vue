<template>
  <div id="app">
    <router-view></router-view>
    <main-tab-bar class="tab"></main-tab-bar>
  </div>
</template>

<script>
  import MainTabBar from 'components/content/mainTabbar/MainTabBar.vue'

  export default {
    name: 'App',
    components: {
      MainTabBar
    }
  }
</script>

<style>
  @import "assets/css/base.css";
  .tab {
    z-index: 19;
  }
</style>
