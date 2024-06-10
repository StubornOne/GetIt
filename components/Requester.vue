<template>
  <div class="container">
    <select name="method" id="method">
      <option value="get">GET</option>
      <option value="post">POST</option>
      <option value="delete">DELETE</option>
    </select>
    <input type="text" class="url">
  </div>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
.container {
  display: flex;
  gap: 1rem;
}

select {
  background: black;
  border: 2px solid rgb(0, 119, 103);
  width: 4rem;
  height: 2rem;
  border-radius: 0.4rem;
  transition: all 0.4s;
}

select:hover {
  border: 2px solid rgb(0, 195, 169);
}

.url {
  height: 2rem;
  width: 50rem;
}
</style>