<template>
  <UCard>
    <template #header>
      <UButton to="https://maps.app.goo.gl/BWHhqaTC2MtLazjP6">Otwórz w Google Maps</UButton>
    </template>

    <iframe class="w-full aspect-video"
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4217.753827214869!2d16.183805513264534!3d53.06246579580905!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47014c297779b531%3A0xe7a13bcc8459f822!2zS2_Fm2Npw7PFgiDFm3cuIErDs3plZmEgdyBEcnpvbm93aWUgV2HFgmVja2lt!5e1!3m2!1spl!2spl!4v1724846649704!5m2!1spl!2spl"
      height="600" style="border:0;" allowfullscreen="" loading="lazy"
      referrerpolicy="no-referrer-when-downgrade"></iframe>

    <template #footer>
      Termin:<br />
      <UBadge>16:00</UBadge><br />
      <UBadge>31 sierpnia 2024</UBadge>
    </template>
  </UCard>
</template>

<script setup lang="ts">
useHead({
  title: 'Ślub',
  meta: [
    { name: 'description', content: 'Informacje o ślubie' }
  ],
})
</script>