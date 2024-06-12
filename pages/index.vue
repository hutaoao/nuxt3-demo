<script setup lang="ts">

</script>

<template>
  <div>
    <h1>Welcome to the homepage</h1>
    <NuxtLink to="/about">About page</NuxtLink>
    <hr>
    <h2>读取 public 里面图片</h2>
    <img src="/img/img1.png" alt="Discover Nuxt 3" width="300"/>
    <hr>
    <h2>读取 assets 里面图片</h2>
    <img src="~/assets/img/img1.png" alt="Discover Nuxt 3" width="300"/>
  </div>
</template>


<style scoped>

</style>