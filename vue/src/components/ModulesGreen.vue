<template>
  <div :class="$style.wrapper">
    <h2>This should be green</h2>
    <slot />
  </div>
</template>

<style module>
.wrapper {
  background: lime;
  color: black;
}
</style>
