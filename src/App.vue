<script setup>
import SocialMedia from "./components/SocialMedia.vue";
import ProfileCard from "./components/Profile.vue";
import Projects from "./components/Projects.vue";
import Skills from "./components/Skills.vue";
</script>

<template>
  <div class="top-grid">
    <ProfileCard />
    <Projects />
    <SocialMedia />
    <Skills />
  </div>
</template>

<style scoped>
.top-grid {
  height: 100%;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: repeat(2, 1fr);
  gap: 20px;
  * {
    border-radius: 30px;
    padding: 20px;
    background-color: var(--color-background-mute);
    box-shadow: 0 0 5px var(--color-background-mute);
    accent-color: var(--accent-color);
  }
}
</style>
