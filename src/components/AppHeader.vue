<script>
export default {
  data() {
    return { 
      contents: 'Questo è un dato preso da AppHeader'
    };
  },
};
</script>

<template>
  <header>
    <h1>
      {{ contents }}
    </h1>
  </header>
</template>

<style scoped>
  h1 {
    background-color: aquamarine;
    color: lightcoral;
    text-align: center;
  }

</style>
