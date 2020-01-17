<template>
  <header class="header container mx-auto h-16 flex flex-row">
    <div class="flex content-center flex-auto w-3/16 h-full">
      <g-image src="~/images/devign-wordmark.svg" width="200" />
    </div>
    <div class="flex content-center header--links flex-initial self-end h-full">
      <span>
        <a href="#work">Proces</a>
      </span>
      <span>
        <a href="#work">Prototype</a>
      </span>
      <span>
        <a href="#work">Reflectie</a>
      </span>
    </div>
    <div class="w-2/16"></div>
  </header>
</template>

<style>
.header .header--links span {
  @apply px-8;
  margin: auto;
}

.header .header--links span:last-child {
  @apply px-4;
}
</style>

<script>
export default {}
</script>
