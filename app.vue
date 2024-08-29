<template>
  <div class="container mx-auto">
    <h1 class="text-3xl font-bold mt-5">Ślub Joli i Pawła</h1>
    <span class="text-lg">31 sierpnia 2024</span>
    <NavBar class="mt-5" />
    <NuxtPage />
    <UDivider class="mt-3" icon="material-symbols-light:favorite" />
    <p class="px-3">
      Kontakt:<br />
      Jola <ULink to="tel:669522353">669 522 353</ULink><br />
      Paweł <ULink to="tel:692248774">692 248 774</ULink>
    </p>
  </div>
</template>

<style>
body {
  text-align: center;
}
</style>

<script>
export default {
}
</script>