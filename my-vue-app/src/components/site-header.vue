<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  name: 'SiteHeader',
  props: {
    title: {
        type: String,
        required: true,
    }
  }
}
</script>

<style scoped>
header {
  background-color: #42b983;
  padding: 15px;
  color: white;
  text-align: center;
}
</style>