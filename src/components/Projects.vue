<script setup>
import ProjectCard from "./ProjectCard.vue"
</script>

<template>
	<div>
		<p>Projects</p>
		<div class="sub">
      <ProjectCard link="https://github.com/noctyris/sky" />
      <ProjectCard link="https://github.com/noctyris/pokedex" />
      <ProjectCard link="https://github.com/noctyris/PyXie" />
      <ProjectCard link="https://github.com/noctyris/sky" />
		</div>
		<p>See more on <a href="https://github.com/noctyris">GitHub</a></p>
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
    gap: 20px;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
    height: calc(100% - 4.2rem);
    * {
      border-radius: 20px;
      padding: 10px;
    }
	}
	a {
    text-decoration: none;
    color: var(--accent-color);
  }
}
</style>
