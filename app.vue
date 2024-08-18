<script setup>
useHead({
  title: 'Expose Project', // Replace with the actual project title
  meta: [
    { name: 'description', content: 'A brief description of the Expose project.' }, // Replace with actual project description
    { name: 'keywords', content: 'Expose, SEO, Project, Web Development, etc.' }, // Replace with relevant keywords
    { name: 'author', content: 'Your Name or Company' }, // Replace with actual author or organization name
    { property: 'og:title', content: 'Expose Project' }, // Open Graph for social sharing
    { property: 'og:description', content: 'A brief description of the Expose project.' },
    { property: 'og:type', content: 'website' },
    { property: 'og:url', content: 'https://www.exposeproject.com' }, // Replace with actual URL
    { property: 'og:image', content: 'https://www.exposeproject.com/image.jpg' }, // Replace with actual image URL
    { name: 'twitter:card', content: 'summary_large_image' }, // Twitter card
    { name: 'twitter:title', content: 'Expose Project' },
    { name: 'twitter:description', content: 'A brief description of the Expose project.' },
    { name: 'twitter:image', content: 'https://www.exposeproject.com/image.jpg' }, // Replace with actual image URL
  ],
  link: [
    { rel: 'preconnect', href: 'https://fonts.googleapis.com' },
    { rel: 'preconnect', href: 'https://fonts.gstatic.com', crossorigin: 'anonymous' },
    { rel: 'stylesheet', href: 'https://fonts.googleapis.com/css2?family=Changa:wght@200..800&family=Exo+2:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet' }
  ]
})

</script>

<template>
  <NuxtPage />
</template>

<style>
body {
  margin: 0;
  padding: 0;
}
</style>