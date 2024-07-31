<template>
  <el-button @click="toggleDark()">
    <i inline-block align-middle i="dark:carbon-moon carbon-sun" />

    <span class="ml-2">{{ isDark ? 'Dark' : 'Light' }}</span>
  </el-button>
</template>
<script setup lang="ts">
import { useDark, useToggle } from '@vueuse/core'

const isDark = useDark()
const toggleDark = useToggle(isDark)
// const isDark = useDark()
</script>