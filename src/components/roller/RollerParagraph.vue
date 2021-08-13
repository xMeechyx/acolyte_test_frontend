<template>
  <!-- ICI JE MET UNE CLASSE POUR ASSURER DE NE PAS PASSER MON CSS AUX CHILD-->
  <div class="parentOnly">
    <MyImage/>
    <RollerTitle/>
    <RollerContent/>
  </div>
</template>

<script>
import MyImage from "@/components/roller/MyImage";
import RollerTitle from "@/components/roller/RollerTitle";
import RollerContent from "@/components/roller/RollerContent";
export default {
  name: 'RollerParagraph',
  components: {
    MyImage,
    RollerTitle,
    RollerContent
  }
}
</script>

<style scoped>
.parentOnly{
  /* Layout Properties */
  margin-top: 463px;
  margin-bottom: 213px;
  height: 969px;
  position: relative;
  /* UI Properties */
}
</style>
