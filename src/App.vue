<template>
  <div id="app" class="demo">
    <local-button label="局部按钮"></local-button>
  </div>
</template>

<script>
import LocalButton from "./components/LocalButton.vue";
export default{
  name: "App",
  components: {
    "local-button": LocalButton
    // LocalButton
  }
}
</script>