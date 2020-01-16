<template>
  <div>
    <div class="h-64 flex flex-col justify-center" id="work">
      <h1 class="text-center">Hoe wij te werk gaan</h1>
    </div>
    <div class="mb-32">
      <div class="flex mx-auto justify-center">
        <a href="#proces" @click="setArea('PROCES')">
          <SwitchButton :isActive="proces" title="Proces" emoji="rocket"></SwitchButton>
        </a>
        <a href="#prototype" @click="setArea('PROTOTYPE')">
          <SwitchButton :isActive="prototypes" title="Prototype" emoji="computer"></SwitchButton>
        </a>
        <a href="#reflectie" @click="setArea('REFLECTIE')">
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
    <Readmore
      :proces="computedProces"
      :prototypes="computedPrototypes"
      :reflectie="computedReflectie"
      v-on:navigate="navigate($event)"
    />
  </div>
</template>

<script>
import SwitchButton from '~/components/SwitchButton.vue'
import Proces from '~/components/Proces.vue'
import Prototypes from '~/components/Prototypes.vue'
import Reflectie from '~/components/Reflectie.vue'
import Readmore from '~/components/Readmore.vue'

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
    navigate(event) {
      this.setArea(event)
    },
    setArea(area) {
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
  computed: {
    computedProces() {
      return !this.proces
    },
    computedPrototypes() {
      return !this.prototypes
    },
    computedReflectie() {
      return !this.reflectie
    }
  },
  components: {
    SwitchButton,
    Proces,
    Prototypes,
    Reflectie,
    Readmore
  }
}
</script>
