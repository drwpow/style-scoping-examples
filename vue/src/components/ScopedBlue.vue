<template>
  <div class="wrapper">
    <h2>This should be blue</h2>
    <slot />
  </div>
</template>

<style scoped>
.wrapper {
  background: navy;
  color: white;
}
</style>
