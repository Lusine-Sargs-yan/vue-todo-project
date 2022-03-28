<template>
  <button :class="mode">
    <slot></slot>
  </button>
</template>

<script>
export default {
  name: "BaseButton",
  props: ['mode'],
}
</script>

<style scoped>
button {
  padding: 0.75rem;
  font-family: inherit;
  background-color: #3a0061;
  border: 1px solid #3a0061;
  cursor: pointer;
}

button:hover,
button:active {
  background-color: #270041;
  border-color: #270041;
}
.flat {
  background-color: transparent;
  color: #3a0061;
}
.flat:hover,
flat:active {
  background-color: #edd2ff;
}
</style>