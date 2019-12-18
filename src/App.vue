<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
@import "~bulma/sass/utilities/_all";

$aqua: hsl(171,100%,41%);
$aqua-invert: findColorInvert($aqua);

$colors: (
  "aqua": ($aqua, $aqua-invert)
);

@import "~bulma";
@import "~buefy/src/scss/buefy";
</style>
