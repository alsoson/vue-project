<template lang="pug">
#left-update
  | {{ date }}
</template>

<script setup>
import { ref } from 'vue'
const date = ref(new Date().toLocaleDateString())
</script>
