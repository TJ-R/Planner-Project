<script setup>

</script>

<template>
  <div class="day-container">
    <div class="hour-divider"></div>
    <div class="hour-divider"></div>
    <div class="hour-divider"></div>
    <div class="hour-divider"></div>
  </div>
</template>

<style scoped>
  .day-container {
    display: flex;
    flex-direction: column;
    gap: 50px;
    align-items: center;
    border: solid red;
    width: 600px;
    height: 800px;
    padding: 200px 0;
  }
  .hour-divider {
    background-color: slategray;
    width: 400px;
    height: 1px;
  }
</style>