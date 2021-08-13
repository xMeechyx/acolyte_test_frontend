<template>
  <!-- ICI JE MET UNE CLASSE POUR ASSURER DE NE PAS PASSER MON CSS AUX CHILD-->
  <div class="parentOnly">
    <ThirdTitle/>
    <ThirdSubtitle/>
  </div>
</template>

<script>
import ThirdTitle from "@/components/thirdTitle/ThirdTitle";
import ThirdSubtitle from "@/components/thirdTitle/ThirdSubtitle";
export default {
  name: 'ThirdTitleBox',
  components: {
    ThirdTitle,
    ThirdSubtitle
  }
}
</script>

<style scoped>
.parentOnly{
  /* Layout Properties */
  margin-top: 213px;
  margin-left: 416px;
  width: 1088px;
  height: 281px;
  position: relative;
  border-style: groove;
  border-color: black;
  border-width: 1px;
  /* UI Properties */
}
</style>
