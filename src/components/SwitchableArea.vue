<template>
  <div>
    <div class="h-64 flex flex-col justify-center">
      <h1 class="text-center">Hoe wij te werk gaan</h1>
    </div>
    <div class="mb-32">
      <div class="flex mx-auto justify-center">
        <a href="#" @click="setArea('PROCES')">
          <SwitchButton :isActive="proces" title="Proces" emoji="rocket"></SwitchButton>
        </a>
        <a href="#" @click="setArea('PROTOTYPE')">
          <SwitchButton :isActive="prototypes" title="Prototype" emoji="computer"></SwitchButton>
        </a>
        <a href="#" @click="setArea('REFLECTIE')">
          <SwitchButton :isActive="reflectie" title="Reflectie" emoji="eye"></SwitchButton>
        </a>
      </div>
    </div>
    <Proces v-if="proces">
      <slot></slot>
    </Proces>
    <Prototypes v-else-if="prototypes">
      <slot></slot>
    </Prototypes>
    <Reflectie v-else-if="reflectie">
      <slot></slot>
    </Reflectie>
  </div>
</template>

<script>
import SwitchButton from '~/components/SwitchButton.vue'
import Proces from '~/components/Proces.vue'
import Prototypes from '~/components/Prototypes.vue'
import Reflectie from '~/components/Reflectie.vue'

export default {
  data() {
    return {
      area: 'PROCES',
      proces: true,
      prototypes: false,
      reflectie: false
    }
  },
  methods: {
    setArea(area) {
      console.log(area)
      this.proces = false
      this.prototypes = false
      this.reflectie = false
      if (area === 'PROCES') {
        this.proces = true
      } else if (area === 'PROTOTYPE') {
        this.prototypes = true
      } else if (area === 'REFLECTIE') {
        this.reflectie = true
      }
    }
  },
  components: {
    SwitchButton,
    Proces,
    Prototypes,
    Reflectie
  }
}
</script>
