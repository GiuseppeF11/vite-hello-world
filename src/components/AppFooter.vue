<script>
export default {
  data() {
    return { 
      contents: 'Questo è un dato preso da AppFooter'
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
    background-color: rgb(102, 232, 171);
    color: rgb(21, 92, 164);
    text-align: center;
  }

</style>