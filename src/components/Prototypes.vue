<template>
  <div>
    <div class="h-40 flex flex-col justify-center">
      <Streepje />
      <h1 class="text-center" id="prototype">Prototype</h1>
    </div>
    <Hoofdstuk :number="1" title="Implementatie fase" />
    <UserStoryMap />
    <DemoDay />
    <Eindconcept />
  </div>
</template>

<script>
import Streepje from '~/components/Streepje.vue'
import Hoofdstuk from '~/components/Hoofdstuk.vue'
import UserStoryMap from '~/components/UserStoryMap.vue'
import DemoDay from '~/components/DemoDay.vue'
import Eindconcept from '~/components/Eindconcept.vue'

export default {
  components: {
    Streepje,
    Hoofdstuk,
    UserStoryMap,
    DemoDay,
    Eindconcept
  }
}
</script>

