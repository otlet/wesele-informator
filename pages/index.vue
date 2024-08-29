<script setup lang="ts">
const route = useRoute()
useHead({
  title: 'Ślub Joli i Pawła',
  meta: [
    { name: 'description', content: 'Szczegółowe informacje o ślubie i weselu' }
  ],
})
</script>

<template>
  <div class="px-3">
    <UButton to="/slub" class="mt-5">O ślubie</UButton><br />
    <UButton to="/wesele" class="mt-5">O weselu</UButton><br />
    <UButton to="/autobus" class="mt-5">O transporcie dla weselników</UButton><br />
  </div>
</template>
