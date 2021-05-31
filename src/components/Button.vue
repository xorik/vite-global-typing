<template>
  <button>Hello</button>
</template>

<script setup lang="ts">
import { defineProps } from 'vue'

const props = defineProps({
  size: {
    type: String,
    required: true,
  },
})
</script>
