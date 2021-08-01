<template>
  <button :class="mode">
    <slot></slot>
  </button>
</template>

<script>
export default {
  props: ['mode']
}
</script>

<style scoped>
button {
  padding: 0.75rem 1.5rem;
  font-family: inherit;
  background-color: #E55689;
  border: 1px solid #E55689;
  border-radius: 5px;
  color: white;
  cursor: pointer;
}

button:hover,
button:active {
  background-color: #5E4FA5;
  border-color: #5E4FA5;
}

.flat {
  background-color: transparent;
  color: #5E4FA5;
  border: 1px solid #5E4FA5;
}

.flat:hover,
.flat:active {
  background-color: #5E4FA5;
  color: white;
}
</style>