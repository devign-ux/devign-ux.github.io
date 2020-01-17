<template>
  <div>
    <div class="h-40 flex flex-col justify-center">
      <Streepje />
      <h1 class="text-center" id="reflectie">Reflectie</h1>
    </div>
    <Hoofdstuk :number="1" title="Reflectie" />
    <ReflectieText />
  </div>
</template> 

<script>
import Streepje from '~/components/Streepje.vue'
import Hoofdstuk from '~/components/Hoofdstuk.vue'
import ReflectieText from '~/components/ReflectieText'

export default {
  components: {
    Streepje,
    Hoofdstuk,
    ReflectieText
  }
}
</script>
