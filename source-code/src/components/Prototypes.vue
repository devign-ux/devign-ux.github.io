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
    <Guidelines />
    <EindPrototype />
    <Testresultaten />
    <Quote2 />
  </div>
</template>

<script>
import Streepje from '~/components/Streepje.vue'
import Hoofdstuk from '~/components/Hoofdstuk.vue'
import UserStoryMap from '~/components/UserStoryMap.vue'
import DemoDay from '~/components/DemoDay.vue'
import Eindconcept from '~/components/Eindconcept.vue'
import Testresultaten from '~/components/Testresultaten.vue'
import Guidelines from '~/components/Guidelines.vue'
import EindPrototype from '~/components/EindPrototype.vue'
import Quote2 from '~/components/Quote2.vue'

export default {
  components: {
    Streepje,
    Hoofdstuk,
    UserStoryMap,
    DemoDay,
    Eindconcept,
    Testresultaten,
    Guidelines,
    EindPrototype,
    Quote2
  }
}
</script>

