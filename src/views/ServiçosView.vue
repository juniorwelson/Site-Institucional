<template>
  <serviços1/>
  <servicos/>
  <nomesujo/>
  <logo/>
</template>

<script>
import serviços1 from '../components/serviços.vue';
import servicos from '../components/areadeservicos.vue';
import nomesujo from '@/components/nomesujo.vue';
import logo from '@/components/logoEmpresas.vue';

export default {
  name: 'ServiçosView',
  components: {
    serviços1,
    servicos,
    nomesujo,
  logo

  }
}
</script>

