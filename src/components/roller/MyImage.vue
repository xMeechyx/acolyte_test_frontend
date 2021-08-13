<template>
  <div>
    <img :src="require('../../assets/images.jpg')"/>
  </div>
</template>

<script>
export default {
  name: 'MyImage'
}
</script>

<style scoped>
div {
  /* Layout Properties */
  margin-top: 0;
  margin-left: 278px;
  width: 646px;
  height: 969px;
  position: absolute;
  z-index: 1;
  /* UI Properties */
}
</style>
