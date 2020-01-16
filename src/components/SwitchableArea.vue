<template>
  <div>
    <div>
      <h1 class="text-center">Hoe wij te werk gaan</h1>
    </div>
    <div>
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
    <Proces v-if="proces"></Proces>
    <Prototypes v-else-if="prototypes"></Prototypes>
    <Reflectie v-else-if="reflectie"></Reflectie>
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
