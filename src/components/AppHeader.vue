<script>
export default {
  data() {
    return { 
      title: 'Hello World'
    };
  },
};
</script>

<template>
  <header>
    <h1 class="main-title">
      {{ title }}
    </h1>
  </header>
</template>

<style scoped>
  .main-title {
    background-color: aquamarine;
    color: lightcoral;
    text-align: center;
  }

</style>
