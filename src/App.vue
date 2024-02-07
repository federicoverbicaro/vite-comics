<template>
  <HeaderDc/>
  <MainPrincipal/>
  <FooterDC/>
</template>

<script scoped>
// Definizione delle opzioni del componente
// import HelloWorld from './components/HelloWorld.vue'; esempio di importazioni di un componente 
import HeaderDc from './components/HeaderDc.vue'
import MainPrincipal from './components/MainPrincipal.vue'
import FooterDC from './components/FooterDc.vue'


//inserimento tag creazione componenti 
export default {

  components: {
    HeaderDc,
    MainPrincipal,
    FooterDC,
  }

}

</script>


<style lang="scss">
/* Stili del componente radice */
@use "../src/styles/general.scss" //collegamento a file general.scss per utilizzare styles
</style>
