<template>
<navBar/>
<headerC/>
<mainC/>
<footerC/>
  <!-- <router-view/> -->
</template>
<script>
import headerC from '@/components/headerC.vue'
import mainC from '@/components/mainC.vue'
import footerC from '@/components/footerC.vue'
import navBar from '@/components/navBar.vue'
export default {
  components: {headerC, footerC, mainC, navBar}
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
