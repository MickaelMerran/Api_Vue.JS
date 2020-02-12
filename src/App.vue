<template>
  <div>
    <navbar></navbar>
    <router-view></router-view>
  </div>
</template>

<script>
import navbar from "./views/navbar.vue"
  export default {
      name: 'App',
      components: {
          navbar,
      },

  }
</script>

<style>

</style>
