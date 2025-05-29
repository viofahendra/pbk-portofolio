<script setup>
import { ref } from 'vue';
const navigasi = ref([
    { name: "Home", href: "#home" },
    { name: "Skill", href: "#skill" },
    { name: "Education", href: "#education" },
    { name: "Project", href: "#project" },
])
</script>

<template>
    <div class="flex justify-around items-center w-full p-6 fixed top-0 bg-white/10 z-50 primary">
        <div>
            <h1 class="text-2xl font-bold tracking-wide uppercase text-primary drop-shadow-md">
                Portofolio
            </h1>
        </div>
        <nav>
            <ul class="flex items-center gap-8 text-lg font-medium">
                <li v-for="nav in navigasi" :key="nav.name">
                    <a :href="nav.href" class="hover:text-blue-300 transition-all duration-300 ease-in-out">
                        {{ nav.name }}
                    </a>
                </li>
            </ul>
        </nav>
    </div>
</template>

<style scoped>
.primary {
    color: #8A784E;

}
</style>