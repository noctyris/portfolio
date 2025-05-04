<script setup>
import SocialMediaCard from "./SocialMediaCard.vue"
</script>

<template>
	<div class="container">
		<p class="title">SocialMedia</p>
		<div class="sm-container">
			<SocialMediaCard
				link="https://instagram.com/hoel__"
				img="instagram.svg"
			/>
			<SocialMediaCard
				link="https://www.astroimg.com/user/525148765653307395"
				img="astroimg.webp"
			/>
			<SocialMediaCard
				link="https://github.com/noctyris"
				img="github.svg"
			/>
			<SocialMediaCard
				link="https://www.linkedin.com/in/hoel-jamier-564b06327"
				img="linkedin.ico"
			/>
		</div>
	</div>
</template>

<style scoped>
.container {
	grid-column-start: 2;
	grid-column-end: 2;
	grid-row-start: 1;
	grid-row-end: 2;
}
.sm-container {
	display: grid;
	align-items: center;
	justify-content: center;
	gap: 1rem;
	grid-template-columns: repeat(3, 1fr);
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
