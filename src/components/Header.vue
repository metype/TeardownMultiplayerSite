<script setup>

</script>

<template>
  <div class="tdmp-header-container">
    <img class="tdmp-img" width="1920" height="576" src="@/assets/tdmp.png" alt="Image taken from Teardown of two characters posing with tools in front of an explosion. The text 'TDMP' is written in the center.">
    <h3 class="tdmp-text">TDMP</h3>
  </div>
</template>

<style scoped>
  div.tdmp-header-container {
    position: relative;
    text-align: center;
  }

  img.tdmp-img {
    width: 100vw;
    height: 20rem;
    object-fit: cover;
  }

  h3.tdmp-text {
    font-size: 7.5rem;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-shadow: #181818 3px 3px;
    user-select: none;
  }
</style>