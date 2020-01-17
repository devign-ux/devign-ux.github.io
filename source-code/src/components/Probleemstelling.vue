<!-- <template>
  <div class="probleemstelling bg-grey-light pt-20 h-64">
    <div class="container flex">
      <div class="w-2/16"></div>
      <div class="w-1/2 p-16">
        <p class="text-magenta h-8">Probleemstelling</p>
        <p
          class="pl-4 border-l-8 border-magenta font-bold"
        >Dagelijks zitten duizenden patiënten in Nederland urenlang in behandeling. Vooral oudere patiënten komen hierdoor nauwelijks in beweging, waardoor ze alleen maar ongezonder worden.</p>
      </div>
      <div class="w-1/2 p-16">
        <p class="h-8 text-magenta">Ontwerpopgave</p>
        <p>Het in beweging krijgen van een oudere patiënt tijdens een behandeling van minimaal 2 uur in het ziekenhuis op de Oncologie, Geriatrie of Dialyse afdeling waarbij ook voor afleiding gezorgd wordt. De VR-beelden moeten een rustgevende en afleidende functie hebben</p>
      </div>
    </div>
  </div>
</template>

<style>
.probleemstelling {
  height: 24rem;
}
</style> -->

<template>
  <div class="bg-grey-light py-16">
    <Box class="flex">
      <div class="w-4/12">
        <p class="text-magenta h-8">Probleemstelling</p>
        <p
          class="pl-4 border-l-8 border-magenta font-bold"
        >Dagelijks zitten duizenden patiënten in Nederland urenlang in behandeling. Vooral oudere patiënten komen hierdoor nauwelijks in beweging, waardoor ze alleen maar ongezonder worden.</p>
      </div>
      <div class="w-2/12"></div>
      <div class="w-6/12">
        <p class="h-8 text-magenta">Ontwerpopgave</p>
        <p>Het in beweging krijgen van een oudere patiënt tijdens een behandeling van minimaal 2 uur in het ziekenhuis op de Oncologie, Geriatrie of Dialyse afdeling waarbij ook voor afleiding gezorgd wordt. De VR-beelden moeten een rustgevende en afleidende functie hebben</p>
      </div>
    </Box>
  </div>
</template>

<script>
import Box from '~/components/Box.vue'

export default {
  components: {
    Box
  }
}
</script>
