<script setup lang="ts">
useHead({
  title: 'My Profile Page',
  meta: [
    { name: 'description', content: 'My amazing Profile Page.' },
    { name: 'keywords', content: 'ahmad, ghanavati, pageProfile' },

  ]
})
useSeoMeta({
  title: 'My Profile Page 1 Site',
  ogTitle: 'My Profile Page 2 Site',
  description: 'This is my Profile Page 1 site, let me tell you all about it.',
  ogDescription: 'This is my Profile Page 2 site, let me tell you all about it.',
  ogImage: 'https://i.pinimg.com/280x280_RS/ff/f6/97/fff69761480787df4fdfa78afbec4ea1.jpg',
  twitterTitle: 'My Profile Page 2 Site twitterTitle',
  twitterDescription: 'My Profile Page 2 Site twitterDescription',
  twitterImage: 'https://i.pinimg.com/280x280_RS/ff/f6/97/fff69761480787df4fdfa78afbec4ea1.jpg',
  twitterCard: 'summary_large_image',
})
</script>

<template>
  <div>
    <h1> Profile Page </h1>
    <nuxt-link to="/"> Profile Page </nuxt-link>
  </div>
</template>

<style scoped>

</style>