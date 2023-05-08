<script setup lang="ts">
import config from './config.json'
import { useVueFlow, VueFlow } from '@vue-flow/core'

useVueFlow(config)
</script>

<template>
  <VueFlow />
</template>

<style scoped></style>
