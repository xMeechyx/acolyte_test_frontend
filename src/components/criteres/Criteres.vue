<template>
  <!-- ICI JE MET UNE CLASSE POUR ASSURER DE NE PAS PASSER MON CSS AUX CHILD-->
  <div class="parentOnly">
    <SecondTitle/>
    <Structure/>
    <Modularite/>
    <Fidelite/>
  </div>
</template>

<script>
import SecondTitle from "@/components/criteres/SecondTitle";
import Structure from "@/components/criteres/Structure";
import Modularite from "@/components/criteres/Modularite";
import Fidelite from "@/components/criteres/Fidelite";

export default {
  name: 'Criteres',
  components: {
    SecondTitle,
    Structure,
    Modularite,
    Fidelite
  }
}
</script>

<style scoped>
.parentOnly{
  /* Layout Properties */
  margin-top: 100px;
  margin-bottom: 53px;
  /* UI Properties */
}
</style>
