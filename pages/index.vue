<template>

  <main>
    
    <section-header></section-header>

    <section-cover></section-cover>

    <section-about></section-about>

    <section-products></section-products>
    
    <section-contact></section-contact>

    <section-footer></section-footer>
    
  </main>
  
</template>

<script setup>

  useHead({
    title: 'Início Móveis Planejados'
  });

</script>

<style scoped>

  main {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

</style>