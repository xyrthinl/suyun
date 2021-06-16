<template>
  <div id="app">
    <header-box></header-box>
    <router-view/>
  </div>
</template>

<script>
import HeaderBox from '@/components/header'
export default {
  name: 'app',
  components:{
    HeaderBox
  }
}
</script>

<style>
#app {
  
}
</style>
