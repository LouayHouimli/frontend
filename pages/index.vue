<script setup>
useSeoMeta({
  ogTitle: "Home",
  ogDescription: "Louay Anime - A streaming service ",
  ogUrl: useRoute().fullPath,
  twitterTitle: "Home",
  twitterDescription: "Louay Anime - A streaming service ",
  twitterCard: "summary",
});

useHead({
  htmlAttrs: {
    lang: "en",
  },
  title: "Home",
});
</script>

<template>
  <PgCompsLandingPage />
</template> 

<style></style>