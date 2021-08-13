<template>
  <div>
    <p>Modularité</p>
    Chaque composante doit être indépendante l’une de l’autre. (ie: pas de body class, pas de IDs, etc.) Déplacer une composante à un autre endroit ne devrait pas tout briser.
  </div>
</template>

<script>
export default {
  name: 'Modularite'
}
</script>

<style scoped>
p {
  /* Layout Properties */
  font: normal normal bold 22px/32px "HelveticaNeue";
  /* UI Properties */
}
div {
  /* Layout Properties */
  margin-top: 53px;
  margin-left: 85px;
  width: 398px;
  height: 145px;
  float: left;
  /* UI Properties */
  text-align: center;
  font: normal normal 300 18px/30px Helvetica Neue;
  color: #000000;
}
</style>
