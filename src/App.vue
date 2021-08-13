<template>
  <div>
    <Title/>
    <Introduction/>
    <Criteres/>
    <RollerParagraph/>
    <ThirdTitleBox/>
    <Congolist/>
    <Conclusion/>
    <SurpriseBtn/>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Introduction from './components/Introduction.vue'
import Criteres from './components/criteres/Criteres.vue'
import RollerParagraph from '@/components/roller/RollerParagraph';
import ThirdTitleBox from './components/thirdTitle/ThirdTitleBox';
import Congolist from '@/components/congo/CongoList';
import Conclusion from './components/Conclusion.vue';
import SurpriseBtn from './components/SurpriseBtn.vue';

/* ----- Je ne crois pas avoir besoin de commenter partout, le code est tres facile a lire selon moi, chaque component est clairement identifier et en ordre, comprenent quelques groupes de components ----- */

export default {
  name: 'App',
  components: {
    Title,
    Introduction,
    Criteres,
    RollerParagraph,
    ThirdTitleBox,
    Congolist,
    Conclusion,
    SurpriseBtn
  }
}
</script>

<style>
div {
  /* Layout Properties */
  /* UI Properties */
  background: #FFFFFF 0% 0% no-repeat padding-box;
  opacity: 1;
}
</style>
