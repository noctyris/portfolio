<template>
	<div>
		<img src="/noctyris.svg" />
		<p id="name">Noctyris</p>
	</div>
</template>

<style scoped>
div {
	grid-row-start: 1;
	grid-row-end: 2;
	display: flex;
	flex-direction: column;
	align-items: center;
	img {
    max-width: 90%;
    border-radius: 25%
	}
	#name {
    margin-top: 20px;
	}
}
</style>
