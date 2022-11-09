<script>
// #1 importo qui eventuali componenti
import { AppTitle } from "./components/AppTitle.vue";
export default {
  // #2 definisco una proprietá components per registrare i componenti importati al punto 1
  components: {
    AppTitle
  }

}



</script>


<template>
  <AppTitle />
</template>


<style>

</style>
