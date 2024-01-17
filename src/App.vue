<script>

/* Per usare un componente dentro un altr:
1) Importazione del componente 
2) Dichiarazione del componente all'interno dell'oggetto
3) Utilizzo del componente
*/

//1)
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  data() {
    return { 
      content: 'Questo è un dato preso da AppVue'
    };
  },
  
  //2) Dichiarazione dei componenti
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  }
}
</script>

<template>
  <div>
    <!-- 3) Utilizzo del componente -->
      <AppHeader/>
      <AppMain/>
      <AppFooter/>
      <h1>
        {{ content }}
      </h1>
  </div>
</template>

<style scoped>
  h1 {
    background-color: red;
    text-align: center;
  }
</style>
