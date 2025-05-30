<template>
  <section id="education" class="min-h-screen py-25 w-full bg-gradient-to-b from-primary to-black text-white">
    <h2 class="text-4xl md:text-6xl font-bold mb-10 text-center animate-slide-in-left">
      Education
    </h2>
    <div class="max-w-4xl mx-auto space-y-10">
      <div v-for="edu in education" :key="edu.school" class="bg-secondary bg-opacity-80 rounded-lg p-6 shadow-lg animate-slide-in-left">
        <h3 class="text-2xl font-semibold mb-1 text-primary">{{ edu.school }}</h3>
        <p class="italic text-gray-300 mb-2">{{ edu.period }}</p>
        <p class="text-xl font-medium mb-3">{{ edu.degree }}</p>
        <p class="text-gray-200">{{ edu.description }}</p>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from 'vue';

const education = ref([
  {
    school: "Universitas Islam Riau",
    degree: "Bachelor of Computer Science",
    period: "2023 - Now",
    description: "Focused on software engineering, data structures, and algorithms."
  },
  {
    school: "SMAN 1 TANAH PUTIH TANJUNG MELAWAN",
    degree: "High School Diploma - Science Major",
    period: "2020 - 2023",
    description: "Concentration in mathematics and physics."
  },
]);
</script>
