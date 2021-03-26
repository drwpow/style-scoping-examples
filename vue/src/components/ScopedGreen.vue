<template>
  <div class="wrapper">
    <h2>This should be green</h2>
    <slot />
  </div>
</template>

<style scoped>
.wrapper {
  background: lime;
  color: black;
}
</style>
