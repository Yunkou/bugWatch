<template>
  <div>
    <router-link to="list">日志列表</router-link>
    
    <bug-compare></bug-compare>
    <div id="top-wrap">
      <page-bug ></page-bug>
      <top-bug ></top-bug>
    </div>
  </div>
  
</template>
<script>
import BugCompare from './bugCompare.vue';
import pageBug from './pageBug.vue';
import topBug from './topBug.vue';
export default {
  data() {
  return {
    msg: 'Welcome to Your Vue.js App',
  };
},
components: {
  BugCompare,
  pageBug,
  topBug,
},
};
</script>
<style>
  #top-wrap {
    margin-top: 10%;
  }
</style>