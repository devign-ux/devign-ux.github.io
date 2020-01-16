<template>
  <div>
    <div class="h-40 flex flex-col justify-center">
      <Streepje />
      <h1 class="text-center" id="proces">Proces</h1>
    </div>
    <Hoofdstuk :number="1" title="Discovery fase" />
    <MethodCards />
    <Hoofdstuk :number="2" title="Ideation fase" />
    <Brainstormen />
    <ConceptCards />
  </div>
</template>

<script>
import Streepje from '~/components/Streepje.vue'
import Hoofdstuk from '~/components/Hoofdstuk.vue'
import MethodCards from '~/components/MethodCards.vue'
import Brainstormen from '~/components/Brainstormen.vue'
import ConceptCards from '~/components/ConceptCards.vue'

export default {
  components: {
    Streepje,
    Hoofdstuk,
    MethodCards,
    Brainstormen,
    ConceptCards
  }
}
</script>

