<script setup>
const props = defineProps(["link", "img", "name"])
</script>

<template>
  <a :href="link" class="project-card" target="_blank">
    <img :src="'/projects/' + props.img"/>
    <p>{{ props.name }}</p>
  </a>
</template>

<style>
.project-card {
  height: 100px;
  overflow: hidden;
  display: flex;
  flex-direction: row;
  align-items: center;
  img {
    width: 75px;
    object-fit: cover;
    margin: 0 10px 0 -10px;
  }
}
</style>