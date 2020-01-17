<template>
  <div class="footer bg-grey-light">
    <Box>
      <h2 class="text-coal py-12 text-center" id="contact">Contact</h2>
      <div class="flex justify-between">
        <div class="flex flex-col">
          <p class="pb-4">Demi</p>
          <a href="https://www.linkedin.com/in/demi-van-duiven-8207b712b/" target="_blank">
            <g-image src="~/images/linkedin.png" width="24" height="24"></g-image>
          </a>
        </div>
        <div class="flex flex-col">
          <p class="pb-4">Dionne</p>
          <a href="https://www.linkedin.com/in/dionne-de-vries-14868a139/" target="_blank">
            <g-image src="~/images/linkedin.png" width="24" height="24"></g-image>
          </a>
        </div>
        <div class="flex flex-col">
          <p class="pb-4">Gabrielle</p>
          <a href="https://www.linkedin.com/in/gabri%C3%ABlle-van-der-valk/" target="_blank">
            <g-image src="~/images/linkedin.png" width="24" height="24"></g-image>
          </a>
        </div>
        <div class="flex flex-col">
          <p class="pb-4">Geoffrey</p>
          <a href="https://www.linkedin.com/in/geoffrey-westbroek-84873b145/" target="_blank">
            <g-image src="~/images/linkedin.png" width="24" height="24"></g-image>
          </a>
        </div>
        <div class="flex flex-col">
          <p class="pb-4">Sven</p>
          <a href="https://www.linkedin.com/in/sven-hoffmann/" target="_blank">
            <g-image src="~/images/linkedin.png" width="24" height="24"></g-image>
          </a>
        </div>
      </div>
      <p class="py-16 text-center">© Devign 2020</p>
    </Box>
  </div>
</template>

<style>
.footer {
  margin-top: 30rem;
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
