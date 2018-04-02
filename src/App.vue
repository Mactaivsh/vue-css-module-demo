<template>
  <div :class="$style.app">
    <img src="./assets/img/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  },
  created() {
    console.log(this.$style)
  }
}
</script>

<style lang="scss" module>
@import './assets/sass/App.module.scss';
</style>