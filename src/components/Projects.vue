<script setup>
import ProjectCard from "./ProjectCard.vue"
</script>

<template>
	<div class="container">
		<p class="title">Projects</p>
		<div class="sub">
      <ProjectCard link="https://sky-noctyris.vercel.app" img="moon.jpg" name="Sky" />
      <ProjectCard link="https://pokedex-he.vercel.app" img="pokedex.svg" name="Pokedex" />
      <ProjectCard link="https://github.com/noctyris/PyXie" img="pyxie.png" name="PyXie" />
      <ProjectCard link="https://github.com/noctyris/spaceshooter" img="spaceshooter.png" name="SpaceShooter" />
		</div>
		<!-- <p>See more on <a href="https://github.com/noctyris">GitHub</a></p> -->
	</div>
</template>

<style scoped>
.container {
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
    height: calc(100% - 10rem);
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
.title {
  font-size: 1.2rem;
  font-weight: 900;
  color: var(--color-text);
  transition: all 0.3s ease-in-out;
}
.container:hover .title {
  color: whitesmoke;
  text-shadow: 0 0 10px white;
}
</style>
