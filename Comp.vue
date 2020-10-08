<template>
  <div class="comp">
    <h3>一个简单计数器</h3>
    <p>{{ count }}</p>
    <button @click="count++">+</button>
    <button @click="count--">-</button>
  </div>
</template>

<script>
export default {
  data: () => ({ count: 0 })
}
</script>

<style scoped>
button {
  color: red;
  margin-right: 10px;
  width: 25px;
  height: 22px;
  text-align: center;
}
</style>
