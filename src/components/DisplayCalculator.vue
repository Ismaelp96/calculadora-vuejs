<template>
  <div class="display">{{ value }}</div>
</template>

<script>
export default {
  props: ['value'],
}
</script>

<style>
.display {
  grid-column: span 4;
  background-color: #0004;

  display: flex;
  justify-content: flex-end;
  align-items: center;
  font-size: 2.1rem;
  padding: 2rem;
  overflow: hidden;
}
</style>
