<template>
  <div id="nav">
    <m-header></m-header>
    <tab></tab>
  </div>
  <router-view/>
</template>
<script>
import Header from '@/components/header/header'
 import Tab from '@/components/tab/tab'
export default {
  components: {
    MHeader: Header,
    Tab
  }
}
</script>

<style lang="scss">

</style>
