<template>
  <div id="app">
    <router-view></router-view>
   <main-tab-bar/>
  </div>
</template>

  <script>
// import MainTabBar from 'components/content/maintabbar/MainTabBar.vue'
// import MainTabBar from 'components/MainTabBar.vue'
import MainTabBar from 'components/content/MainTabBar'

  export default {
    name:'app',
    components: {
      MainTabBar

    },
  }
  </script>
<style>
@import 'assets/css/base.css';
</style>
