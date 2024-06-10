<template>
  <div class="container">
    <slot />
  </div>
</template>

<script lang="ts" setup>

</script>

<style lang="scss">
.container {
  background: linear-gradient(#171717, #2c2c2c);
  height: 100vh;
  padding: 0.5rem 0.5rem 0 0.5rem;
  overflow: hidden;
}

* {
  margin: 0;
  box-sizing: border-box;
  color: white;
}
</style>