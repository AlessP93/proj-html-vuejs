<template>
  <div id="app">
    <baseNav/>
    <BaseHeader/>
    <BaseMain/>
    <BaseFooter/>
  </div>
</template>

<script>
import BaseNav from './components/blocks/BaseNav.vue'
import BaseHeader from './components/blocks/BaseHeader.vue'
import BaseMain from './components/blocks/BaseMain.vue'
import BaseFooter from './components/blocks/BaseFooter.vue'

export default {
  name: 'App',
  components: {
    BaseNav,
    BaseHeader,
    BaseMain,
    BaseFooter
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss';
@import './assets/style/global-parts/variables.scss';
</style>
