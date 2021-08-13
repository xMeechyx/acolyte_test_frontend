<template>
  <div v-on:click="handle()"><p>SURPRISE</p></div>
</template>

<script>
export default {
  name: 'SurpriseBtn',
  /*-------- Handler pour le Bouton SURPRISE qui ouvre un popup :) --------*/
  methods: {
  handle(){
    window.open('https://www.youtube.com/watch?v=njos57IJf-0', '_blank');
    console.log('Un peu mieu que Rick Roll ;)')
  }
 }
}
</script>

<style scoped>
p {
  font: normal normal bold 30px/30px Montserrat;
  color: #FFFFFF;
  text-align: center;
}
div {
  /* Layout Properties */
  margin-top: 47px;
  margin-left: 830px;
  margin-right: 830px;
  margin-bottom: 201px;
  width: 260px;
  height: 82px;
  /* UI Properties */
  background: #000000 0% 0% no-repeat padding-box;
  border: 1px solid #000000;
  border-radius: 10px;
  opacity: 1;
}
</style>
