<template>
  <div :class="$style.wrapper">
    <h2>This should be blue</h2>
    <slot />
  </div>
</template>

<style module>
.wrapper {
  background: navy;
  color: white;
}
</style>
