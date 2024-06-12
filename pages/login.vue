<script setup lang="ts">
const title = ref('我是登录页')

definePageMeta({
  pageTransition: {
    name: 'bounce',
    mode: 'out-in' // default
  }
})
</script>

<template>
  <Head>
    <Title>{{ title }}</Title>
    <Meta name="description" :content="title"/>
    <Style type="text/css" children="body { background-color: #eee; }"></Style>
  </Head>

  <section>
    <h1>login page</h1>
  </section>
</template>

<style scoped>

</style>