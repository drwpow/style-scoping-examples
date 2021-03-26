<template>
  <h1>Scoped Styles</h1>
  <ScopedBlue>
    <ScopedGreen>
      <ScopedBlue>
        <ScopedGreen>
          <ScopedBlue />
        </ScopedGreen>
      </ScopedBlue>
    </ScopedGreen>
  </ScopedBlue>

  <h1>CSS Modules</h1>
  <ModulesGreen>
    <ModulesBlue>
      <ModulesGreen>
        <ModulesBlue />
      </ModulesGreen>
    </ModulesBlue>
  </ModulesGreen>
</template>

<script>
import ScopedBlue from "./components/ScopedBlue.vue";
import ScopedGreen from "./components/ScopedGreen.vue";
import ModulesBlue from "./components/ModulesBlue.vue";
import ModulesGreen from "./components/ModulesGreen.vue";

export default {
  name: "App",
  components: {
    ScopedBlue,
    ScopedGreen,
    ModulesBlue,
    ModulesGreen,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}

h1 {
  margin-bottom: 1rem;
  margin-top: 4rem;
}
</style>
