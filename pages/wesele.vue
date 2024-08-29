<template>
  <UCard>
    <template #header>
        <UAlert
            icon="material-symbols:map-sharp"
            color="red"
            variant="subtle"
            title="Google Maps źle pokazuje drogę!"
            description="Link powinien Was kierować głównymi drogami, aż do stacji paliw w Wałczu, a potem na ulicę polną w kierunku Wałcz Pierwszy."
            class="mb-4"
        />
        <UButton to="https://maps.app.goo.gl/zqSFfuAVgtidk1YF6">Otwórz w Google Maps</UButton>
    </template>

    <iframe class="w-full aspect-video" src="https://www.google.com/maps/embed?pb=!1m32!1m12!1m3!1d269224.45409846614!2d16.12874676481696!3d53.1759720452343!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m17!3e0!4m5!1s0x47014c297779b531%3A0xe7a13bcc8459f822!2zS2_Fm2Npw7PFgiDFm3cuIErDs3plZmEgdyBEcnpvbm93aWUgV2HFgmVja2ltLCBEcnpvbm93byBXYcWCZWNraWUsIDc4LTYzMA!3m2!1d53.062397399999995!2d16.1862907!4m3!3m2!1d53.2894436!2d16.4364264!4m5!1s0x47015d3adbb9a3d1%3A0xc5f1ce51724cfb6a!2sMAKI%20El%20Paso%2C%2039%2C%2078-600%20Wa%C5%82cz%20Pierwszy!3m2!1d53.284493399999995!2d16.4144519!5e1!3m2!1spl!2spl!4v1724847808404!5m2!1spl!2spl" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  </UCard>
</template>

<script setup lang="ts">
useHead({
  title: 'Wesele',
  meta: [
    { name: 'description', content: 'Informacje o weselu' }
  ],
})
</script>
