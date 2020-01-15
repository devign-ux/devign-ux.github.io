<template>
  <div class="mx-auto">
    <slot />
    <link rel="stylesheet" href="https://use.typekit.net/les1qnk.css" />
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>
body {
  margin: 0;
  padding: 0;
  @apply text-coal;
  @apply bg-white;
  @apply font-body;
}

html {
  font-size: 16px;
}

@screen xl {
  html {
    font-size: 18px;
  }
}

@font-face {
  font-family: 'Metropolis';
  src: url('/fonts/Metropolis-ExtraBold.eot');
  src: url('/fonts/Metropolis-ExtraBold.woff') format('woff'),
    url('/fonts/Metropolis-ExtraBold.woff2') format('woff2'),
    url('/fonts/Metropolis-ExtraBold.otf') format('opentype');
}

h1,
h2 {
  @apply font-display;
}

p {
  @apply font-body;
  @apply text-coal;
  @apply text-base;
  @apply leading-normal;
}

a {
  @apply text-magenta;
  @apply underline;
}

h1 {
  @apply text-xl;
  @apply text-coal;
  @apply font-extrabold;
}

h2 {
  @apply text-lg;
  @apply text-magenta;
  @apply font-medium;
}

@screen lg {
  h1 {
    @apply text-2xl;
  }

  h2 {
    @apply text-xl;
  }
}
</style>
