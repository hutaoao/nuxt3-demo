<template>
  <div>
    <NuxtLayout>
      <NuxtPage/>
    </NuxtLayout>
  </div>
</template>

<script setup lang="ts">
// useHead({
//   title: '我的第一个nuxt应用',
//   meta: [
//     {name: 'description', content: 'My amazing site.'}
//   ],
//   bodyAttrs: {
//     class: 'test'
//   },
//   script: [{innerHTML: 'console.log(\'Hello world\')'}]
// })

useSeoMeta({
  title: '我的第一个nuxt应用',
  ogTitle: 'My Amazing Site',
  description: 'This is my amazing site, let me tell you all about it.',
  ogDescription: 'This is my amazing site, let me tell you all about it.',
  ogImage: 'https://example.com/image.png',
  twitterCard: 'summary_large_image',
})
</script>

<style>
.layout-enter-active,
.layout-leave-active {
  transition: all 0.4s;
}

.layout-enter-from,
.layout-leave-to {
  filter: grayscale(1);
}
</style>