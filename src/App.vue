<script>
import MenuLateral from "@/components/MenuLateral.vue";
import CabecalhoHeader from "@/components/CabecalhoHeader.vue";
import PrincipalContent from "@/components/PrincipalContent.vue";
import RodapeFooter from "./components/RodapeFooter.vue";


export default {
  components: { MenuLateral, CabecalhoHeader, PrincipalContent, RodapeFooter },
};
</script>
<template>
  <MenuLateral />
  <CabecalhoHeader />
  <PrincipalContent />
  <RodapeFooter />
</template>
<style>
</style>
