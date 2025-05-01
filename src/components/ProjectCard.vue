<script setup>
const props = defineProps(["link"])
</script>

<template>
  <a :href="link">
    <p>{{ props.link }}</p>
  </a>
</template>
