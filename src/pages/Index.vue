<template>
  <Layout>
    <Header />
    <Hero />
    <Keywords />
    <SwitchableArea />
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

export default {
  components: {
    Copy,
    SwitchableArea,
    Header,
    Hero,
    Keywords
  }
}
</script>
