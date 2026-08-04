<script setup>
defineProps({
  page: { type: String, required: true },
  tone: { type: String, default: 'light' },
  label: { type: String, default: 'WORKSTYLES' },
})
</script>

<template>
  <div class="slide-chrome" :class="`chrome-${tone}`">
    <div class="chrome-brand">FREELANCE ENGINEER BIBLE</div>
    <div class="chrome-right">
      <span>{{ label }}</span>
      <span class="chrome-page">{{ page }} / 14</span>
    </div>
  </div>
</template>
