<template>
  <div class="name">
    <h1>{{ name }}</h1>
  </div>
</template>

<script>
export default {
  props: ["name"],
};
</script>

<style scoped>
.name {
  position: absolute;
  margin: auto;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  width: 500px;
  height: 100px;
}
h1 {
  text-align: center;
}
</style>
