<template>
  <div>
    <SiteHeader title="Вітаю у Vue-додатку!" />
  </div>
</template>

<script>
import SiteHeader from './components/site-header.vue'

export default {
  components: {
    SiteHeader
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
