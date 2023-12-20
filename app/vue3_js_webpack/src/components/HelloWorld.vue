<template>
  <div class='hello'>

    {{ name }}
    <button @click="name++">name++</button>
  </div>
</template>

<script  setup>
import { ref } from 'vue'
let name = ref(0)
</script>

<style scoped lang='less'></style>
