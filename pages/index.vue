<script setup lang="ts">
useHead({
  title: 'My Index Page',
  meta: [
    { name: 'description', content: 'My amazing Index Page.' },
    { name: 'keywords', content: 'ahmad, ghanavati, pageIndex' },

  ]
})
useSeoMeta({
  title: 'My Index Page 1 Site',
  ogTitle: 'My Index Page 2 Site',
  description: 'This is my Index Page 1 site, let me tell you all about it.',
  ogDescription: 'This is my Index Page 2 site, let me tell you all about it.',
  ogImage: 'https://i.pinimg.com/280x280_RS/ff/f6/97/fff69761480787df4fdfa78afbec4ea1.jpg',
  twitterTitle: 'My Index Page 2 Site twitterTitle',
  twitterDescription: 'My Index Page 2 Site twitterDescription',
  twitterImage: 'https://i.pinimg.com/280x280_RS/ff/f6/97/fff69761480787df4fdfa78afbec4ea1.jpg',
  twitterCard: 'summary_large_image',
})
</script>

<template>
<div>
  <h1> Index Page </h1>
  <p> <nuxt-link to="/profile"> Profile Page </nuxt-link> </p>
  <p> <nuxt-link to="/blog/article-1"> Article 1 Page </nuxt-link> </p>
  <p> <nuxt-link to="/blog/article-2"> Article 2 Page </nuxt-link> </p>
  <p> <nuxt-link to="/b/134"> 134 Page </nuxt-link> </p>
  <p> <nuxt-link to="/b/555"> 555 Page </nuxt-link> </p>
</div>
</template>

<style scoped>

</style>