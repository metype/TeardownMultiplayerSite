<script setup>

</script>

<template>
  <div class="text-container">
    <div class="internal-text-container">
      <h2>{{title}}</h2>
      <p>{{text}}</p>
    </div>
  </div>
</template>

<script lang="ts">
  export default {
    props: ['title', 'text'],
  }
</script>

<style scoped>
  div.text-container {
    width: 90vw;
    margin: 1rem 5vw;
    display: inline-block;
    background-color: var(--color-background-mute);
  }

  div.internal-text-container {
    margin: 0.5rem;
  }
</style>