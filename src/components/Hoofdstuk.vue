<template>
  <div class="flex">
    <div class="w-2/16"></div>
    <div class="flex flex-col justify-center hoofdstuk text-grey-light">
      <span class="font-display font-black">{{displayedNumber}}</span>
      <h1 class="text-grey-light">{{displayedTitle}}</h1>
    </div>
  </div>
</template>

<style>
.hoofdstuk {
  height: 24rem;
}

.hoofdstuk span {
  font-size: 10rem;
  line-height: 9rem;
}

.hoofdstuk h1 {
  font-size: 3.3333rem;
}
</style>

<script>
export default {
  props: {
    number: Number,
    title: String
  },
  computed: {
    displayedNumber() {
      return this.number || 0
    },
    displayedTitle() {
      return this.title || 'Geen titel'
    }
  }
}
</script>
