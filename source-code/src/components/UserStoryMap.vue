<template>
  <div class="flex mb-32 bg-grey-light pt-16">
    <div class="w-2/16"></div>
    <div class="w-4/16">
      <span class="text-magenta mb-4">User story map</span>
      <h1 class="mb-4">Plannen laatste sprint</h1>
      <p>In deze uitwerking zijn de userstories te zien die in de laatste fase van het project zijn aangemaakt. Deze stories zijn weer onderverdeeld in taken die gekoppeld zijn aan de verschillende rollen in het team.</p>
      <a
        href="https://miro.com/welcomeonboard/RTeKz3dfNAsWvEUIJpp3s1BWcIO3vMkHUkthD8yhCBXKQOFDFgdvLVaz3co36gnV"
        target="_blank"
      >Bekijk de User story map</a>
    </div>
    <div class="w-1/16"></div>
    <div class="userstorymap w-9/16">
      <g-image src="~/images/userstorymap.png"></g-image>
    </div>
  </div>
</template>

<style>
.userstorymap {
  transform: translateY(4rem);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
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
