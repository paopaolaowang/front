<template>
  <div id="app">
    <my-header/>
    <router-view/>
    <my-footer/>
  </div>
</template>
<script>
  import myFooter from '@/components/Footer'
  import myHeader from '@/components/Header'
  export default {
    components: {
      myFooter,
      myHeader
    },
  }
</script>
<style lang="scss">
@import './assets/layui/css/layui.css';
</style>
