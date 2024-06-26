<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
   <RouterLink to="/">首页</RouterLink>
   <RouterLink to="/article">文章</RouterLink>
   <RouterLink to="/about">关于</RouterLink>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  display: flex;
  justify-content: flex-end;
  line-height: 54px;
  height: 54px;
  background-color:lightgoldenrodyellow;
  padding-right: 15px;
}
header a{
  width: 60px;
  height: 54px;
  text-align: center;
}
</style>
