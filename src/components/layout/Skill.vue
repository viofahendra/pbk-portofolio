<template>
    <section id="skill" class="min-h-screen mt-10 w-full flex flex-col justify-center items-center text-center
           bg-gradient-to-b from-primary to-black text-white">
        <h2 class="text-4xl md:text-6xl font-bold mb-12 animate-slide-in-left">
            My <span class="text-primary">Skills</span>
        </h2>
        <div class="grid grid-cols-3 gap-10 max-w-5xl w-full">
            <div v-for="skill in skills" :key="skill.name"
                class="bg-white/10 rounded-lg p-6 shadow-lg hover:bg-primary/80 transition cursor-default">
                <h3 class="text-2xl font-semibold mb-3">{{ skill.name }}</h3>
                <div class="h-2 bg-gray-700 rounded-full overflow-hidden">
                    <div class="h-full bg-primary transition-all duration-700" :style="{ width: skill.level + '%' }">
                    </div>
                </div>
                <p class="mt-3 text-gray-300 text-sm">{{ skill.description }}</p>
            </div>
        </div>
    </section>
</template>

<script setup>
import { ref } from 'vue';

const skills = ref([
    { name: 'HTML & CSS', level: 95, description: 'Building semantic and responsive layouts' },
    { name: 'JavaScript', level: 90, description: 'Interactive web features and logic' },
    { name: 'Vue.js', level: 85, description: 'Building reactive and performant SPAs' },
    { name: 'Tailwind CSS', level: 80, description: 'Utility-first styling with responsiveness' },
    { name: 'Java', level: 80, description: 'Robust, platform-independent programming' },
    { name: 'Python', level: 85, description: 'Versatile scripting and data processing' },
]);
</script>
