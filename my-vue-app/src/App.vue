<script>
// #1 importo qui eventuali componenti
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  // #2 definisco una proprietá components per registrare i componenti importati al punto 1
  components: {
    AppTitle,
    AppHero,
  }

}



</script>


<template>
  <AppTitle />
  <AppHero />
</template>


<style>

</style>
