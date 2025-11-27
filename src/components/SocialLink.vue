<template>
  <a class="social-link" :href="url" target="_blank" rel="noopener noreferrer">
    <span class="icon">{{ icon }}</span>
    {{ label }}
  </a>
</template>

<script setup>
const props = defineProps({
  icon: String,
  label: String,
  url: String
});
</script>
