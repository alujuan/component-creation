<script>
import MenuLateral from "@/components/MenuLateral.vue";
import BlocoPrincipal from "@/components/BlocoPrincipal.vue";
import BlocoCabecalho from "@/components/BlocoCabecalho.vue";
import BlocoRodape from "@/components/BlocoRodape.vue";
export default {
  components: { MenuLateral, BlocoPrincipal, BlocoRodape, BlocoCabecalho },
};
</script>
<template>
  <BlocoCabecalho />
  <MenuLateral />
  <BlocoPrincipal />
  <BlocoRodape />
</template>
<style></style>
