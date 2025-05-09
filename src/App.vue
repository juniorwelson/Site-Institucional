<template>
 <navbar/>
 
  <router-view/>
  <rodape/>
</template>

<script>
import navbar from './components/navbar.vue';
import Rodape from './components/rodape.vue';

export default {
  name:'App',
  components:{
    navbar,
    Rodape
   
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Libre+Baskerville&display=swap');

  *{

    font-family: 'Libre Baskerville', 'serif';
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  
}

 
</style>
