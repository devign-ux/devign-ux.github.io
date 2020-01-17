<template>
  <div class="my-32">
    <h1 class="text-center my-16">Guidelines</h1>
    <Box class="guidelines flex flex-wrap">
      <div class="w-1/4 p-4">
        <h1 class="flex-col text-magenta-light">1</h1>
        <p>Er moet een optie zijn voor het gebruiken van de trappers</p>
      </div>
      <div class="w-1/4 p-4">
        <h1 class="flex-col text-magenta-light">2</h1>
        <p>De gefilmde beelden mogen niet misselijk makend zijn</p>
      </div>
      <div class="w-1/4 p-4">
        <h1 class="flex-col text-magenta-light">3</h1>
        <p>Er moet rekening gehouden worden met slechtziend of horende mensen</p>
      </div>

      <div class="w-1/4 p-4">
        <h1 class="flex-col text-magenta-light">4</h1>
        <p>Het moet voor iedereen makkelijk te begrijpen zijn</p>
      </div>
      <div class="w-1/4 p-4">
        <h1 class="flex-col text-magenta-light">5</h1>
        <p>Het concept moet zoveel mogelijk zintuigen aanspreken</p>
      </div>
      <div class="w-1/4 p-4">
        <h1 class="flex-col text-magenta-light">6</h1>
        <p>Er moeten genoeg route opties mogelijk zijn</p>
      </div>
      <div class="w-1/4 p-4">
        <h1 class="flex-col text-magenta-light">7</h1>
        <p>Het concept moet voldoen aan een rustgevende en afleidende functie binnen alle content</p>
      </div>
      <div class="w-1/4 p-4">
        <h1 class="flex-col text-magenta-light">8</h1>
        <p>De patiënten moeten in beweging gebracht worden</p>
      </div>
    </Box>
  </div>
</template>

<style>
.guidelines h1 {
  font-size: 4rem;
}
</style>

<script>
import Box from '~/components/Box.vue'

export default {
  components: {
    Box
  }
}
</script>
