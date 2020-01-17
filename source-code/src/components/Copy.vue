<template>
  <div class="copy">
    <slot />
  </div>
</template>

<style>
.copy h1 + p {
  @apply mt-1;
}

.copy h2 + p {
  @apply mt-1;
}

.copy * + h1,
h2 {
  @apply mt-2;
}

.copy p + p {
  @apply mt-2;
}
</style>

<script>
export default {
  name: 'Copy'
}
</script>
