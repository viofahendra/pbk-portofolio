<script setup>
import profileImage from '../../assets/profile.jpg'
</script>

<template>
    <section id="home" class="min-h-screen mt-20 w-full flex flex-col justify-center items-center text-center
           bg-gradient-to-b from-primary to-black text-white">
        <div class="flex flex-row items-center gap-10 p-8 w-full">
            <!-- Teks -->
            <div class="flex-1 flex flex-col items-center">
                <h2 class="text-4xl md:text-6xl font-bold mb-6 animate-slide-in-left">
                    👋 Hi, I'm <span class="text-primary">Vio Fahendra</span>
                </h2>

                <p class="text-lg text-center md:text-xl max-w-lg mb-8 text-gray-200 animate-slide-in-left">
                    A passionate <span class="font-semibold text-white">Web Developer</span> with a strong focus on
                    creating responsive, user-friendly, and visually appealing websites. Dedicated to writing clean code
                    and
                    delivering seamless digital experiences through modern web technologies.
                </p>

                <a href="#project"
                    class="inline-block px-8 py-3 bg-primary text-secondary font-semibold rounded-full hover:bg-white/20 transition animate-slide-in-left shadow-md mb-6">
                    View My Projects
                </a>

                <!-- Social Icons -->
                <div class="flex gap-6 text-white text-2xl animate-slide-in-left">
                    <!-- Instagram -->
                    <a href="https://www.instagram.com/vioofhndra._" target="_blank" rel="noopener" aria-label="Instagram"
                        class="hover:text-primary transition">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                            <path
                                d="M7.75 2A5.75 5.75 0 0 0 2 7.75v8.5A5.75 5.75 0 0 0 7.75 22h8.5A5.75 5.75 0 0 0 22 16.25v-8.5A5.75 5.75 0 0 0 16.25 2h-8.5Zm0 1.5h8.5c2.356 0 4.25 1.894 4.25 4.25v8.5c0 2.356-1.894 4.25-4.25 4.25h-8.5C5.394 20.5 3.5 18.606 3.5 16.25v-8.5C3.5 5.394 5.394 3.5 7.75 3.5Zm8.75 2.25a1 1 0 1 0 0 2 1 1 0 0 0 0-2Zm-5 1.25a4.5 4.5 0 1 0 0 9 4.5 4.5 0 0 0 0-9Zm0 1.5a3 3 0 1 1 0 6 3 3 0 0 1 0-6Z" />
                        </svg>
                    </a>

                    <!-- GitHub -->
                    <a href="https://github.com/viofahendra" target="_blank" rel="noopener" aria-label="GitHub"
                        class="hover:text-primary transition">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                            <path
                                d="M12 2a10 10 0 0 0-3.16 19.49c.5.09.68-.22.68-.48v-1.7c-2.78.6-3.37-1.34-3.37-1.34-.45-1.15-1.1-1.46-1.1-1.46-.9-.62.07-.6.07-.6 1 .07 1.53 1.03 1.53 1.03.89 1.52 2.34 1.08 2.91.82.09-.64.35-1.08.63-1.33-2.22-.25-4.55-1.11-4.55-4.94 0-1.09.39-1.98 1.03-2.67-.1-.25-.45-1.26.1-2.63 0 0 .84-.27 2.75 1.02a9.56 9.56 0 0 1 5 0c1.91-1.29 2.75-1.02 2.75-1.02.55 1.37.2 2.38.1 2.63.64.69 1.03 1.58 1.03 2.67 0 3.84-2.34 4.69-4.57 4.94.36.31.68.92.68 1.86v2.76c0 .26.18.57.69.48A10 10 0 0 0 12 2Z" />
                        </svg>
                    </a>

                    <!-- WhatsApp -->
                    <a href="https://wa.me/6285349351900" target="_blank" rel="noopener" aria-label="WhatsApp"
                        class="hover:text-primary transition">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                            <path
                                d="M20.52 3.48A11.83 11.83 0 0 0 12.04.3c-3.13 0-6.06 1.22-8.26 3.43A11.63 11.63 0 0 0 0 11.95c0 2.12.55 4.15 1.6 5.96L0 24l6.28-1.64a11.83 11.83 0 0 0 5.76 1.47h.01c3.13 0 6.06-1.22 8.26-3.43A11.63 11.63 0 0 0 24 11.96c0-3.17-1.23-6.15-3.48-8.48Zm-8.48 17.2h-.01c-1.74 0-3.43-.47-4.92-1.36l-.35-.21-3.73.97 1-3.64-.22-.38a9.4 9.4 0 0 1-1.41-5.02c0-5.14 4.18-9.32 9.33-9.32a9.3 9.3 0 0 1 6.6 15.91 9.3 9.3 0 0 1-6.3 2.05Zm5.12-6.94c-.28-.14-1.64-.81-1.9-.9-.26-.1-.44-.14-.63.14-.19.28-.73.9-.89 1.09-.16.19-.33.21-.61.07-.28-.14-1.2-.44-2.29-1.4-.85-.76-1.43-1.7-1.6-1.98-.16-.28-.02-.43.12-.57.12-.13.28-.33.42-.49.14-.17.19-.28.28-.47.1-.19.05-.36-.02-.5-.07-.14-.63-1.51-.87-2.07-.23-.55-.47-.48-.63-.49h-.54c-.18 0-.47.07-.72.36-.25.28-.96.94-.96 2.3 0 1.36.99 2.67 1.13 2.85.14.19 1.95 2.97 4.73 4.17.66.28 1.18.44 1.58.56.66.21 1.27.18 1.75.11.53-.08 1.64-.67 1.87-1.32.23-.65.23-1.21.16-1.32-.07-.11-.25-.18-.53-.32Z" />
                        </svg>
                    </a>
                </div>
            </div>


            <!-- Gambar Profil -->
            <div class="flex flex-col items-center w-1/3">
                <figure class="flex-1 max-w-sm text-center animate-slide-in-right">
                    <img :src="profileImage" alt="Profile"
                        class="rounded-none object-cover w-full h-auto max-w-[250px] mx-auto " />
                </figure>
                <div class="h-1 w-full bg-amber-100 rounded-b"></div>
            </div>
        </div>
    </section>
</template>

<style scoped>
@keyframes slide-in-left {
    from {
        transform: translateX(-100%);
        opacity: 0;
    }

    to {
        transform: translateX(0);
        opacity: 1;
    }
}

@keyframes slide-in-right {
    from {
        transform: translateY(100px);
        opacity: 0;
    }

    to {
        transform: translateY(0);
        opacity: 1;
    }
}

.animate-slide-in-left {
    animation: slide-in-left 1s ease-out forwards;
}

.animate-slide-in-right {
    animation: slide-in-right 1s ease-out forwards;
}
</style>
