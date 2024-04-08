<script setup lang="ts">
useHead({
  title: 'My Article - 1 Page',
  meta: [
    { name: 'description', content: 'My amazing Article - 1 Page.' },
    { name: 'keywords', content: 'ahmad, ghanavati, pageArticle - 1' },

  ]
})
useSeoMeta({
  title: 'My Article - 1 Page 1 Site',
  ogTitle: 'My Article - 1 Page 2 Site',
  description: 'This is my Article - 1 Page 1 site, let me tell you all about it.',
  ogDescription: 'This is my Article - 1 Page 2 site, let me tell you all about it.',
  ogImage: 'https://i.pinimg.com/280x280_RS/ff/f6/97/fff69761480787df4fdfa78afbec4ea1.jpg',
  twitterTitle: 'My Article - 1 Page 2 Site twitterTitle',
  twitterDescription: 'My Article - 1 Page 2 Site twitterDescription',
  twitterImage: 'https://i.pinimg.com/280x280_RS/ff/f6/97/fff69761480787df4fdfa78afbec4ea1.jpg',
  twitterCard: 'summary_large_image',
})
</script>

<template>
  <div>
    <h1> Article 1 Page </h1>
    <nuxt-link to="/"> Index Page </nuxt-link>
  </div>
</template>

<style scoped>

</style>