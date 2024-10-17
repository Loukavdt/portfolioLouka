<template>
<div class="w-full h-full no-print">
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup>
useHead({
  title: 'My portfolio',
  meta: [
    { name: 'description', content: 'Example for students' }
  ],
  htmlAttrs: {
    lang: 'en'
  }
})
</script>