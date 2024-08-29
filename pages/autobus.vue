<template>
  <UCard>
    <UAlert icon="material-symbols:map-sharp" color="red" variant="subtle"
      description="Wszelkie kwestie mogą ulec zmianie, o zmianach będziemy informować!" class="mb-4" />
    <UDivider label="Transport po weselu" class="mb-3" />
    <iframe class="w-full aspect-video"
      src="https://www.google.com/maps/embed?pb=!1m42!1m12!1m3!1d269136.0773954545!2d16.135173766805767!3d53.19005334416518!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m27!3e0!4m5!1s0x47015d3adbb9a3d1%3A0xc5f1ce51724cfb6a!2sMAKI%20El%20Paso%2C%2039%2C%2078-600%20Wa%C5%82cz%20Pierwszy!3m2!1d53.284493399999995!2d16.4144519!4m5!1s0x47015d70ab96ce87%3A0xbe6bbb262e20bfb!2sMotel%20Za%20Grosik!3m2!1d53.281927599999996!2d16.453598799999998!4m4!1s0x47015d9af18f19c5%3A0x801e2b08e36b95c!3m2!1d53.277245!2d16.473457!4m4!1s0x47015d9050b4cc25%3A0xb26e20da432763bb!3m2!1d53.276272999999996!2d16.478737!4m3!3m2!1d53.090596!2d16.1222164!5e1!3m2!1spl!2spl!4v1724931627587!5m2!1spl!2spl"
      height="450" style="border:0;" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    <ul class="pl-5">
      <li>
        MAKI El Paso - autobus będzie podstawiony ok. <UBadge>4:00</UBadge>
      </li>
      <li>Koło Motelu Za Grosik</li>
      <li>Przystanek koło Hotelu Biały Domek i Szkoły "Czwórka"</li>
      <li>Przystanek Park koło Stadionu</li>
      <li>Człopa</li>
    </ul>
    <UButton to="https://maps.app.goo.gl/Euh9zoFnURaPD27D7">Pokaż przystanki w Google Maps</UButton>

    <UDivider label="Transport na poprawiny" class="mb-3" />
    <iframe class="w-full aspect-video"
      src="https://www.google.com/maps/embed?pb=!1m42!1m12!1m3!1d269136.0773954545!2d16.135824916805767!3d53.19005334416518!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m27!3e0!4m3!3m2!1d53.090596!2d16.1222164!4m4!1s0x47015d9050b4cc25%3A0xb26e20da432763bb!3m2!1d53.276272999999996!2d16.478737!4m4!1s0x47015d9af18f19c5%3A0x801e2b08e36b95c!3m2!1d53.277245!2d16.473457!4m5!1s0x47015d70ab96ce87%3A0xbe6bbb262e20bfb!2sMotel%20Za%20Grosik!3m2!1d53.281927599999996!2d16.453598799999998!4m5!1s0x47015d3adbb9a3d1%3A0xc5f1ce51724cfb6a!2sMAKI%20El%20Paso%2C%2039%2C%2078-600%20Wa%C5%82cz%20Pierwszy!3m2!1d53.284493399999995!2d16.4144519!5e1!3m2!1spl!2spl!4v1724931595887!5m2!1spl!2spl"
      height="450" style="border:0;" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    <ul class="pl-5">
      <li>
        Człopa <UBadge>Informacja zostanie podana w autobusie</UBadge>
      </li>
      <li>Przystanek Park koło Stadionu</li>
      <li>Przystanek koło Hotelu Biały Domek i Szkoły "Czwórka"</li>
      <li>Koło Motelu Za Grosik</li>
      <li>MAKI El Paso</li>
    </ul>
    <UButton to="https://maps.app.goo.gl/n1vxj55gzPCHtEDi8">Pokaż przystanki w Google Maps</UButton>

  </UCard>
</template>

<script setup lang="ts">
useHead({
  title: 'Transport',
  meta: [
    { name: 'description', content: 'Informacje o ślubie' }
  ],
})
</script>