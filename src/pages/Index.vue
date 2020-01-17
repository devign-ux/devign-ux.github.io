<template>
  <Layout>
    <Header />
    <Hero />
    <Keywords />
    <Belang />
    <Doelen />
    <Quote />
    <Realiseren />
    <Probleemstelling />
    <SwitchableArea />
    <Stakeholders />
    <Quote2 />
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
import Quote from '~/components/Quote.vue'
import Stakeholders from '~/components/Stakeholders.vue'
import Quote2 from '~/components/Quote2.vue'


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
    Quote,
    Stakeholders,
    Quote2
  },
  metaInfo: {
    title: 'VR'
  }
}
</script>
