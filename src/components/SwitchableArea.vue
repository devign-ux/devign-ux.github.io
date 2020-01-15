<template>
  <div>
    <div>
      <div @click="setArea('PROCES')">BUTTON 1 Proces</div>
      <div @click="setArea('PROTOTYPE')">BUTTON 2 Prototypes</div>
      <div @click="setArea('REFLECTIE')">BUTTON 3 Reflectie</div>
    </div>
    <div v-if="proces">PROCES</div>
    <div v-else-if="prototypes">PROTOTYPES</div>
    <div v-else-if="reflectie">REFLECTIE</div>
  </div>
</template>

<script>
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
  }
}
</script>
