<template>
  <TheHeader />

  <main>
    <slot />
  </main>

  <TheFooter />
</template>

<script setup lang="ts">
// import "@/assets/css/style.css";
// import "@/assets/scss/main.scss";

useHead({
  title: "Natours | Exciting tours for adventurous people",
  charset: "utf-8",
  viewport: "width=device-width, initial-scale=1.0",
  link: [
    // { rel: "stylesheet", href: "css/icon-font.css" },
    // { rel: "stylesheet", href: "css/style.css" },
    {
      href: "https://fonts.googleapis.com/css?family=Lato:100,300,400,700,900",
      rel: "stylesheet",
    },
  ],
});
</script>

<style scoped>
/*
COLORS:

Light green: #7ed56f
Medium green: #55c57a
Dark green: #28b485

*/
</style>
