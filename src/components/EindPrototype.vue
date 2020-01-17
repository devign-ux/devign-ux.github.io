<template>
  <div class="flex my-32 py-32 bg-grey-light">
    <div class="w-10/16">
      <g-image class="EP__BOX w-full h-full" src="~/images/goef.png" width="529" height="355"></g-image>
    </div>
    <div class="w-1/16"></div>
    <div class="w-3/16">
      <span class="text-magenta mb-4">Eindprototype</span>
      <h1 class="mb-4">Eindprototype</h1>
      <p>Tijdens de tocht wordt er stil gestaan op verschillende plekken. Tussentijds wordt er geteleporteerd naar een andere plek in de route. Er wordt informatie gegeven door audiofragmenten op de plekken waar bij wordt stilgestaan. Door het teleporteren tussen de stilstaande stukken door moet het bij de gebruiker ervoor zorgen dat ze minder misselijk worden van de bewegende beelden. Er kan een keuze worden gemaakt tussen culturele en geschiedenis tochten.</p>
    </div>
    <div class="w-2/16"></div>
  </div>
</template>
<style>
.EP__BOX {
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
