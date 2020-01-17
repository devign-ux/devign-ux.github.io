<template>
  <Box class="flex flex-row-reverse py-32">
    <div class="flex w-6/12">
      <g-image src="~/images/dit-zeggen-anderen.png" class="self-center" width="533" height="222"></g-image>
    </div>
    <div class="w-1/12"></div>
    <div class="w-5/12">
      <span class="text-magenta mb-4">Testresultaten</span>
      <h1 class="mb-4">Dit zeggen anderen</h1>
      <p
        class="mb-4"
      >Om te achterhalen of het uiteindelijke concept goed zou overkomen en of het gebruiksvriendelijk genoeg was is er voor gekozen om opnieuw testen uit te voeren.</p>
      <p>Het eindprototype is getest bij 5 testpersonen met positieve resultaten. Wegens privacy redenen voor de patiënten was het niet mogelijk om met de echte doelgroep te testen.</p>
    </div>
  </Box>
</template>

<script>
import Box from '~/components/Box.vue'

export default {
  components: {
    Box
  }
}
</script>
