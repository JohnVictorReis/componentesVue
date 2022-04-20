<script>
import MenuLateral from "@/components/MenuLateral.vue";
import CabecalhoTeste from "./components/CabecalhoTeste.vue";
import RodapeVue from "./components/RodapeVue.vue";
import MainPagina from "./components/MainPagina.vue";
export default {
  components: { MenuLateral, CabecalhoTeste, RodapeVue, MainPagina },
};
</script>
<template>
  <MenuLateral />
  <CabecalhoTeste/>
  <MainPagina/>
  <RodapeVue/>
</template>
<style></style>
