<template>
  <!-- ICI JE MET UNE CLASSE POUR ASSURER DE NE PAS PASSER MON CSS AUX CHILD-->
  <div class="parentOnly">
    <Incristaliser/>
    <MyPolygon/>
    <Imposer/>
    <MyPolygon/>
    <Intentionner/>
    <MyPolygon/>
    <CongoText/>
  </div>
</template>

<script>
import Incristaliser from '@/components/congo/Incristaliser.vue'
import MyPolygon from '@/components/congo/MyPolygon.vue'
import Imposer from "@/components/congo/Imposer";
import Intentionner from "@/components/congo/Intentionner";
import CongoText from "@/components/congo/CongoText";

export default {
  name: 'Congolist',
  components: {
    Imposer,
    Incristaliser,
    MyPolygon,
    Intentionner,
    CongoText
  }
}
</script>

<style scoped>
.parentOnly{
  /* Layout Properties */
  /* UI Properties */
}
</style>
