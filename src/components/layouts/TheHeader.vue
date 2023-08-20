<template>
  <header>
    <h1> {{ title }}</h1>
  </header>
</template>

<script>
export default {
  name: "TheHeader",
  props: ['title']
}
</script>

<style scoped>
header {
  width: 100%;
  height: 5rem;
  background-color: #6e2b4c;
  display: flex;
  justify-content: center;
  align-items: center;
}
header h1 {
  color: #fff;
  margin: 0;
}
</style>