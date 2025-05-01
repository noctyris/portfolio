<script setup>
const props = defineProps(["link", "img"])
</script>

<template>
	<div class="card">
        <a :href="link" target="_blank" rel="noopener noreferrer">
            <img :src="img" :alt="name" class="card-img-top" />
        </a>
    </div>
</template>

<style scoped>
.card {
    width: 50px;
    aspect-ratio: 1/1;
}
</style>
