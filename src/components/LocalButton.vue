<template>
  <button @click="handleClick" class="btn">{{ label }}</button>
</template>

<script>
export default {
  props: ["label"],
  methods: {
    handleClick() {
      alert("局部按钮被点击了！")
    }
  }
}
</script>
