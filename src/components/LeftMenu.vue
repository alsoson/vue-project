<template lang="pug">
#left-menu
  h1 社團介紹
  table
    tr(v-for="club in clubs")
      td {{ club }}
</template>

<script setup>
import { reactive } from 'vue'

const clubs = reactive([
  '吉他', '熱舞', '棒球', '羽球', '足球', '童軍'
])
</script>