<script setup>
useHead({
  htmlAttrs: { lang: "en-US" },
  title: "AASE-EMIS Dashboard",
  meta: [
    {
      name: "description",
      content:
        "Get Your Authentic and Accurate Data from AASEDEO EMIS.",
    },
  ],
  bodyAttrs: {
    class: 'font-display'
  }
});
</script>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
