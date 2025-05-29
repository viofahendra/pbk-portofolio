<script setup>
import Header from "./components/layout/Header.vue";
import HeroSection from "./components/layout/HeroSection.vue";
import Skill from "./components/layout/Skill.vue";
import Education from "./components/layout/Education.vue";
import Project from "./components/layout/Project.vue";
</script>

<template>
  <div class="bg-primary min-h-screen flex flex-col justify-center items-center">
    <Header />
    <HeroSection />
    <Skill />
    <Education />
    <Project />
  </div>
</template>

<style scoped></style>
