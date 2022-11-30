<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
<script setup>
useHead({
  title: "Tic tac toe",
  link: [
    {
      rel: "icon",
      type: "image/png",
      href: "/nuxt.png",
    },
  ],
});
</script>
