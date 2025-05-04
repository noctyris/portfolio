<template>
	<div class="container">
		<p class="title">Skills</p>
	</div>
</template>

<style scoped>
.container {
	grid-row-start: 1;
	grid-row-end: 3;
	grid-column-start: 3;
	grid-column-end: 3;
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
