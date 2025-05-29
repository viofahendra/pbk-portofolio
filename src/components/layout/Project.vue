<template>
  <section id="project" class="min-h-screen w-full py-25 bg-gradient-to-b from-black to-primary text-white">
    <h2 class="text-4xl md:text-6xl font-bold mb-10 text-center animate-slide-in-left">
      Projects
    </h2>
    <div class="grid grid-cols-3 gap-6 max-w-6xl mx-auto">
      <div
        v-for="(project, index) in projects"
        :key="index"
        class="bg-secondary bg-opacity-80 rounded-lg overflow-hidden shadow-lg transform hover:scale-105 transition-all duration-300 animate-slide-in-up"
      >
        <img :src="project.image" :alt="'Project ' + (index + 1)" class="w-full h-48 object-cover" />
        <div class="p-4">
          <h3 class="text-xl font-semibold mb-2 text-primary">{{ project.title }}</h3>
          <p class="text-gray-200 text-sm">{{ project.description }}</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from 'vue';
import project1 from "../../assets/project1.jpg"

const projects = ref([
  {
    title: "HTML CSS",
    description: "Landing Page",
    image: project1,
  },
  {
    title: "HTML CSS",
    description: "Profile Page",
    image: "../../src/assets/IMG-20250529-WA0009.jpg",
  },
  {
    title: "HTML CSS",
    description: "Form Register",
    image: "../../src/assets/IMG-20250529-WA0008.jpg",
  },
  {
    title: "HTML CSS",
    description: "Form Login",
    image: "../../src/assets/IMG-20250529-WA0007.jpg",
  },
  {
    title: "HTML CSS",
    description: "Galery Page",
    image: "../../src/assets/IMG-20250529-WA0005.jpg",
  },
  {
    title: "HTML CSS",
    description: "Articel Page",
    image: "../../src/assets/IMG-20250529-WA0006.jpg",
  },
]);
</script>
