<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template lang="pug">
.hello-world
  h1 IS HET VOETBALWEER?
  h1.msg JA
</template>

<style scoped>
h1 {
  font-size: 50pt;
  color: white;
}
</style>
