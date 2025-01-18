<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<style>
  body {
    font-family: 'Roboto Condensed', serif;
  }

  .layout-enter-active,
  .layout-leave-active {
    transition: opacity 0.4s ease-in-out, transform 0.3s ease-in-out;
  }
  .layout-enter-from,
  .layout-leave-to {
    opacity: 0;
    transform: scale(1.2);
    transform-origin: center;
  }
</style>