<template>
  <BarraDeNavegacao />
  <SobreRodolpho />
  <ProjetosRodolpho />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraDeNavegacao from './components/Cabecalho.vue';
import SobreRodolpho from './components/Sobre.vue';
import ProjetosRodolpho from './components/Workspace.vue'

export default defineComponent({
  name: 'App',
  components: {
    BarraDeNavegacao,
    SobreRodolpho,
    ProjetosRodolpho
  }
});

</script>

<style>

</style>
