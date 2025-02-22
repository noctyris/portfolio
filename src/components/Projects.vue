<script setup>
import ProjectCard from "./ProjectCard.vue"
</script>

<template>
	<div>
		<p>Projects</p>
		<div class="sub">
      <p><ProjectCard name="Truc" /></p>
      <p>b</p>
      <p>c</p>
      <p>d</p>
		</div>
	</div>
</template>

<style scoped>
div {
	grid-row-start: 2;
	grid-row-end: 2;
	grid-column-start: 1;
	grid-column-end: 3;
	.sub {
    margin-top: 20px;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
	}
}
</style>
