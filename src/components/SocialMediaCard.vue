<script setup>
const props = defineProps(["link", "img"])
</script>

<template>
	<div class="card">
        <a :href="link" target="_blank" rel="noopener noreferrer">
            <img :src="'/icons/' + img" class="card-img-top" style="object-fit: cover; width: 100%; height: 100%;" />
        </a>
    </div>
</template>

<style scoped>
.card {
    width: 100%;
    height: 100%;
    overflow: hidden;
    transition: all 0.3s ease-in-out;
    max-width: 75px;
    margin: auto;
}
</style>
