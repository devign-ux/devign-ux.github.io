<template>
  <div>
    <div class="h-40 flex flex-col justify-center">
      <Streepje />
      <h1 class="text-center">Proces</h1>
    </div>
    <Hoofdstuk />
  </div>
</template>

<script>
import Streepje from '~/components/Streepje.vue'
import Hoofdstuk from '~/components/Hoofdstuk.vue'

export default {
  components: {
    Streepje,
    Hoofdstuk
  }
}
</script>

