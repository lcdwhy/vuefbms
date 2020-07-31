<template>
  <div id="app">
    <router-link to="/login">login</router-link>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
@import url('./assets/styles/base.css');
</style>
