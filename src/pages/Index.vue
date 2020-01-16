<template>
  <Layout>
    <Header />
    <Hero />
    <Keywords />
      <Belang />
      <Doelen />
      <Realiseren />
      <Probleemstelling />
      <Inzichten/>
    <Copy>
      <h1>Stukje een</h1>
      <p>
        Voorbeeld stukje een. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error
        doloremque omnis animi, eligendi magni a voluptatum, vitae, consequuntur
        rerum illum odit fugit assumenda rem dolores inventore iste
        reprehenderit maxime! Iusto.
      </p>
      <h2>Stukje twee</h2>
      <p>
        Voorbeeld stukje twee. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error
        doloremque omnis animi, eligendi magni a voluptatum, vitae, consequuntur
        rerum illum odit fugit assumenda rem dolores inventore iste
        reprehenderit maxime! Iusto.
      </p>
      <h3>Stukje drie</h3>
      <p>
        Voorbeeld stukje drie. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error
        doloremque omnis animi, eligendi magni a voluptatum, vitae, consequuntur
        rerum illum odit fugit assumenda rem dolores inventore iste
        reprehenderit maxime! Iusto.
      </p>
      <SwitchableArea />
    </Copy>
  </Layout>
</template>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>

<script>
import Copy from '~/components/Copy.vue'
import SwitchableArea from '~/components/SwitchableArea.vue'
import Header from '~/components/Header.vue'
import Hero from '~/components/Hero.vue'
import Keywords from '~/components/Keywords.vue'
import Belang from '~/components/Belang.vue'
import Doelen from '~/components/Doelen.vue'
import Realiseren from '~/components/Realiseren.vue'
import Probleemstelling from '~/components/Probleemstelling.vue'
import Inzichten from '~/components/Inzichten.vue'

export default {
  components: {
    Copy,
    SwitchableArea,
    Header,
    Hero,
    Keywords,
    Belang,
    Doelen,
    Realiseren,
    Probleemstelling,
    Inzichten
  }
}
</script>
