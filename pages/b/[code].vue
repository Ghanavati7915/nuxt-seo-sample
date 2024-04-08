<script setup lang="ts">
const route = useRoute();
const code = ref(route.params.code)

useHead({
  title: `My ${code.value} Page`,
  meta: [
    { name: 'description', content: `My amazing  ${code.value} Page.` },
    { name: 'keywords', content: `ahmad, ghanavati, pageArticle - 1 , ${code.value}` },

  ]
})
useSeoMeta({
  title: `My ${code.value} Page 1 Site`,
  ogTitle: `My ${code.value} Page 2 Site`,
  description: `This is my ${code.value} Page 1 site, let me tell you all about it.`,
  ogDescription: `This is my ${code.value} Page 2 site, let me tell you all about it.`,
  ogImage: 'https://i.pinimg.com/280x280_RS/ff/f6/97/fff69761480787df4fdfa78afbec4ea1.jpg',
  twitterTitle: `My ${code.value} Page 2 Site twitterTitle`,
  twitterDescription: `My ${code.value} Page 2 Site twitterDescription`,
  twitterImage: 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQIUYSbeJNdFjfssxN3gu5he6FRGvrqGTE9TS11VKmbcg&s',
  twitterCard: 'summary_large_image',
})
</script>

<template>
  <div>
    <h1> {{code}} Page </h1>
    <nuxt-link to="/"> Index Page </nuxt-link>
  </div>
</template>

<style scoped>

</style>