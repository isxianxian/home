<template>
  <div class="home">
    <topNav></topNav>
    <Top></Top>
    <Live></Live>
    <Hot></Hot>
    <Exellent></Exellent>
    <botNav></botNav>
  </div>
</template>

<style lang="scss" scoped>
</style>


<script>
import topNav from '../components/topNav.vue';
import Top from '../components/Header.vue';
import Live from '../components/Live.vue';
import Hot from '../components/Hot.vue';
import Exellent from '../components/Exellent.vue';
import botNav from '../components/botNav.vue';

export default {
  name: 'home',
  components: {
    topNav,
    Top,
    Live,
    Hot,
    Exellent,
    botNav
  }
}
</script>
