<template>
  <button @click="handleClick" class="btn">{{ label }}</button>
</template>

<script>
export default {
  props: ["label"],
  methods: {
    handleClick() {
      alert("全局按钮被点击了！")
    }
  }
}
</script>

<style>
.btn {
  padding: 10px;
  background: #42b983;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
</style>
