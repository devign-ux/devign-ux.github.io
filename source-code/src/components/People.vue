<template>
  <!-- I am sorry -->
  <div class="people-block bg-grey-light">
    <h1 class="py-24 text-center">Mede mogelijk gemaakt door</h1>
    <Box class="flex flex-wrap justify-center">
      <g-image class="people-box" src="~/images/1-demi.png"></g-image>
      <g-image class="people-box" src="~/images/2-dionne.png"></g-image>
      <g-image class="people-box" src="~/images/3-gabrielle.png"></g-image>
      <g-image class="people-box" src="~/images/4-geoffrey.png"></g-image>
      <g-image class="people-box" src="~/images/5-sven.png"></g-image>
      <a href="#contact">
        <g-image class="people-box" src="~/images/6-meerweten.png"></g-image>
      </a>
    </Box>
    <h1 class="pt-24 pb-16 text-center">In samenwerking met</h1>
    <p class="text-center pb-16">- SyncVR</p>
  </div>
</template>

<style>
.people-box {
  height: 15rem;
  width: 15rem;
  @apply p-2;
}

.people-block {
  height: 38rem;
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
