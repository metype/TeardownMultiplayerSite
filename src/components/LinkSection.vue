<script setup>

</script>

<template>
  <div class="link-container">
    <div class="internal-link-container">
      <h2>{{title}}</h2>
      <p>{{text}}</p>
      <a class="link" :href="link" target="_blank">{{link_text}}</a>
    </div>
  </div>
</template>

<script lang="ts">
  export default {
    props: ['link', 'title', 'link_text', 'text'],
  }
</script>

<style scoped>
  div.link-container {
    width: 90vw;
    margin: 1rem 5vw;
    display: inline-block;
    background-color: var(--color-background-mute);
  }

  div.internal-link-container {
    margin: 0.5rem;
  }

  a:link, a:visited {
    background-color: var( --color-background-soft );
    color: white;
    padding: 8px 14px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
  }

  a:hover, a:active {
    background-color: var( --color-background );;
  }
</style>