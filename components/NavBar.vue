<script setup lang="ts">
const route = useRoute()

const links = [{
  label: 'Ślub',
  icon: 'material-symbols:church',
  to: '/slub'
}, {
  label: 'Wesele',
  icon: 'material-symbols:music-note',
  to: '/wesele'
}, {
  label: 'Transport',
  icon: 'material-symbols:departure-board-outline-sharp',
  to: '/autobus'
}]
</script>

<template>
  <UHorizontalNavigation :links="links" class="border-b border-gray-200 dark:border-gray-800" />
</template>
