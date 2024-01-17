<script>

/* Per usare un componente dentro un altr:
1) Importazione del componente 
2) Dichiarazione del componente all'interno dell'oggetto
3) Utilizzo del componente
*/

//1)
import AppHeader from './components/AppHeader.vue';

export default {
  data() {
    return { 
      count: 0 
    };
  },
  
  //2) Dichiarazione dei componenti
  components: {
    AppHeader
  }
}
</script>

<template>
  <div>
    <!-- 3) Utilizzo del componente -->
      <AppHeader/>
  </div>
</template>

<style scoped>

</style>
