<template>
  <Box class="my-20">
    <h2 class="text-coal mb-8">Zie ook deze onderwerpen</h2>
    <div class="flex">
      <a v-if="proces" href="#work" @click="$emit('navigate', 'PROCES')">
        <div class="flex border-2 border-magenta rounded py-4 px-6 mr-4">
          <g-image
            src="~/images/emoji-rocket.png"
            background="transparent"
            fit="contain"
            width="33"
            height="43"
          ></g-image>
          <h2 class="text-coal ml-4">Proces</h2>
        </div>
      </a>
      <a v-if="prototypes" href="#work" @click="$emit('navigate', 'PROTOTYPE')">
        <div class="flex border-2 border-magenta rounded py-4 px-6 mr-4">
          <g-image
            src="~/images/emoji-computer.png"
            background="transparent"
            fit="contain"
            width="33"
            height="43"
          ></g-image>
          <h2 class="text-coal ml-4">Prototype</h2>
        </div>
      </a>
      <a v-if="reflectie" href="#work" @click="$emit('navigate', 'REFLECTIE')">
        <div class="flex border-2 border-magenta rounded py-4 px-6">
          <g-image
            src="~/images/emoji-eye.png"
            background="transparent"
            fit="contain"
            width="33"
            height="43"
          ></g-image>
          <h2 class="text-coal ml-4">Reflectie</h2>
        </div>
      </a>
    </div>
  </Box>
</template>

<script>
import Box from '~/components/Box.vue'

export default {
  props: ['proces', 'prototypes', 'reflectie'],
  components: {
    Box
  }
}
</script>
