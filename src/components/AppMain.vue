<script>
export default {
  data() {
    return { 
      contents: 'Questo è un dato preso da AppMain'
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
    background-color: rgb(199, 168, 68);
    color: rgb(164, 21, 21);
    text-align: center;
  }

</style>