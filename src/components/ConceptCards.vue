<!-- <template>
  <div class="concept-cards">
    <div class="concept-cards__block flex justify-center bg-grey-light">
      <div class="concept-cards__card bg-white rounded p-4 mr-4">
        <h2 class="text-coal pb-4">Concept 1</h2>
        <p>Via een speciaal keuzemenu, in de vorm van een ruimte (kamer), kan er worden gekeken naar de foto’s/schilderijen. Ook moet er een aantal seconden gefietst worden om de selectie te bevestigen. Op deze manier worden de trappers op een alternatieve interactieve manier ingezet. Tijdens de tocht worden geschiedenis beelden laten zien om het gevoel van nostalgie nog meer over te brengen.</p>
      </div>
      <div class="concept-cards__card bg-white rounded p-4 mr-4">
        <h2 class="text-coal pb-4">Concept 2</h2>
        <p>Het idee van dit concept was het maken van een Quiz aan het einde van de tocht. Om de antwoorden definitief te selecteren moest er een aantal seconden gefietst worden om zo weer extra interactie met de trappers te hebben. Ook was het idee dat door deze quiz mensen meer zouden opletten tijdens de tocht en zo nog meer afgeleid zouden zijn omdat ze de antwoord op de vragen zullen weten.</p>
      </div>
      <div class="concept-cards__card bg-white rounded p-4">
        <h2 class="text-coal pb-4">Concept 3</h2>
        <p>Tijdens de tocht wordt er stil gestaan op verschillende plekken. Tussentijds wordt er geteleporteerd naar een andere plek in de route. Er wordt informatie gegeven door audiofragmenten op de plekken waar bij wordt stilgestaan. Door het teleporteren tussen de stilstaande stukken door moet het bij de gebruiker ervoor zorgen dat ze minder misselijk worden van de bewegende beelden.</p>
      </div>
    </div>
  </div>
</template>

<style>
.concept-cards {
  height: 30rem;
}

.concept-cards__block {
  height: 20rem;
}

.concept-cards__card {
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
  line-height: 1.3;
  transform: translateY(5rem);
  width: 350px;
  height: 450px;
}
</style>

<script>
export default {}
</script> -->

<template>
  <div class="concept-cards">
    <div class="concept-cards__block bg-grey-light">
      <Box>
        <div class="flex justify-around">
          <div class="concept-cards__card bg-white rounded p-4 mr-4">
            <h2 class="text-coal pb-4">Concept 1</h2>
            <p>Via een speciaal keuzemenu, in de vorm van een ruimte (kamer), kan er worden gekeken naar de foto’s/schilderijen. Ook moet er een aantal seconden gefietst worden om de selectie te bevestigen. Op deze manier worden de trappers op een alternatieve interactieve manier ingezet. Tijdens de tocht worden geschiedenis beelden laten zien om het gevoel van nostalgie nog meer over te brengen.</p>
          </div>
          <div class="concept-cards__card bg-white rounded p-4 mr-4">
            <h2 class="text-coal pb-4">Concept 2</h2>
            <p>Het idee van dit concept was het maken van een Quiz aan het einde van de tocht. Om de antwoorden definitief te selecteren moest er een aantal seconden gefietst worden om zo weer extra interactie met de trappers te hebben. Ook was het idee dat door deze quiz mensen meer zouden opletten tijdens de tocht en zo nog meer afgeleid zouden zijn omdat ze de antwoord op de vragen zullen weten.</p>
          </div>
          <div class="concept-cards__card bg-white rounded p-4">
            <h2 class="text-coal pb-4">Concept 3</h2>
            <p>Tijdens de tocht wordt er stil gestaan op verschillende plekken. Tussentijds wordt er geteleporteerd naar een andere plek in de route. Er wordt informatie gegeven door audiofragmenten op de plekken waar bij wordt stilgestaan. Door het teleporteren tussen de stilstaande stukken door moet het bij de gebruiker ervoor zorgen dat ze minder misselijk worden van de bewegende beelden.</p>
          </div>
        </div>
      </Box>
    </div>
  </div>
</template>

<style>
.concept-cards {
  height: 30rem;
}

.concept-cards__block {
  height: 20rem;
}

.concept-cards__card {
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
  line-height: 1.3;
  transform: translateY(5rem);
  width: 350px;
  height: 450px;
}
</style>

<script>
import Box from '~/components/Box.vue'

export default {
  components: {
    Box
  }
}
</script>
