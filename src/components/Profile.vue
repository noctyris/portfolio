<template>
  <div class="container">
    <p class="title">Noctyris</p>
    <div class="section">
      <p>Student at Sainte-Anne d'Auray (France)</p>
      <p>French Baccalaureate - 1<sup>ère</sup> GT</p>
    </div>
  </div>
</template>

<style scoped>
.container {
  grid-row-start: 1;
  grid-row-end: 2;
  background: url("/noctyris.svg") no-repeat center center;
  background-size: cover;
  .section {
    backdrop-filter: blur(2px) brightness(0.5);
    width: fit-content;
    margin-bottom: 4px;
    padding: 5px;
    border-radius: 10px;
    box-shadow: 0 0 5px var(--color-background-mute);
    color: var(--color-text);
    font-size: 0.9rem;
    font-weight: 900;
    text-shadow: 0 0 5px var(--color-background-mute);
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
