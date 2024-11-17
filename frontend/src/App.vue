<script setup lang="ts">
import AppFooter from "./components/AppFooter.vue";
import ButtonSelector from "./components/ButtonSelector.vue";
</script>

<template>
  <main>
    <h1>Pick'em All</h1>
    <div class="competition-selector">
      <ButtonSelector title="LEC" color="#f17314" />
      <ButtonSelector title="LCK" color="#8574b5" />
      <ButtonSelector title="LPL" color="#ea4335" />
     </div>
  </main>
  <AppFooter />
</template>

<style scoped>
.competition-selector {
  display: flex;
  justify-content: center;
  gap: 2vw;
  margin-top: 30vh;
}
.competition-selector-button {
  padding: 5vh 5.5vw;
  font-size: 2.5em;
}
</style>
