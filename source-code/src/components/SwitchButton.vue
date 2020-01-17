<template>
  <div
    :class="{'switch-button flex flex-col justify-center h-64 w-64 relative rounded-lg bg-magenta-light text-white mx-4': active, 'switch-button flex flex-col justify-center h-64 w-64 relative rounded-lg bg-white text-coal border-2 border-magenta mx-4': standard}"
  >
    <g-image
      v-if="emojiComputed === 'computer'"
      src="~/images/emoji-computer.png"
      background="transparent"
      fit="contain"
      width="33"
      height="43"
      class="mx-auto"
    ></g-image>
    <g-image
      v-else-if="emojiComputed === 'eye'"
      src="~/images/emoji-eye.png"
      background="transparent"
      fit="contain"
      width="33"
      height="43"
      class="mx-auto"
    ></g-image>
    <g-image
      v-else-if="emojiComputed === 'rocket'"
      src="~/images/emoji-rocket.png"
      background="transparent"
      fit="contain"
      width="33"
      height="43"
      class="mx-auto"
    ></g-image>
    <h1 :class="{'mx-auto text-white': active, 'mx-auto text-coal': standard}">{{titleComputed}}</h1>
    <span
      :class="{'switch-button__more-info absolute text-center w-full': active, 'switch-button__more-info absolute text-center w-full text-magenta': standard}"
    >{{bottomText}}</span>
  </div>
</template>

<style>
.switch-button .switch-button__more-info {
  bottom: 1rem;
}

.switch-button {
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}
</style>

<script>
export default {
  props: {
    isActive: Boolean,
    emoji: String,
    title: String
  },
  computed: {
    isActiveComputed() {
      return this.isActive
    },
    emojiComputed() {
      return this.emoji
    },
    titleComputed() {
      return this.title
    },
    bottomText() {
      if (this.active) {
        return 'Meer informatie hieronder'
      } else {
        return 'Lees meer'
      }
    },
    standard() {
      if (this.isActiveComputed) {
        return false
      } else {
        return true
      }
    },
    active() {
      if (this.isActiveComputed) {
        return true
      } else {
        return false
      }
    }
  }
}
</script>
