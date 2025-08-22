<template>
  <div>
    <child-component v-for="msg in messages" :key="msg.id" :message="msg.text" />
  </div>
</template>

<script>
import ChildComponent from "./components/ChildComponent.vue"

export default {
  data(){
    return {
      messages: [
        { id: 1, text: "message 1" },
        { id: 2, text: "message 2" }
      ]
    }
  },
  components: { ChildComponent }
}
</script>