<template>
  <div class="app">
    <router-link to="/login">登陆</router-link>
    <router-link to="/frontpage">首页</router-link>
  </div>
  <router-view />
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
  components: {}
})
</script>
<style lang="scss"></style>
