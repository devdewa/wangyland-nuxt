<template>
  <VitePwaManifest />
  <NuxtLoadingIndicator />
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<style>
  .guides.router-link-active {
    @apply text-indigo-400 border-indigo-400 outfit-600;
  }
  .outfit-200 {
    font-family: Outfit !important;
    font-weight: 200;
  }
  .outfit-300 {
    font-family: Outfit !important;
    font-weight: 300;
  }
  .outfit-400 {
    font-family: Outfit !important;
    font-weight: 400;
  }
  .outfit-500 {
    font-family: Outfit !important;
    font-weight: 500;
  }
  .outfit-600 {
    font-family: Outfit !important;
    font-weight: 600;
  }
  .outfit-800 {
    font-family: Outfit !important;
    font-weight: 800;
  }
</style>