<template>
    <header class="bg-white">
        <nav class="container flex items-center justify-between px-4 py-6 mx-auto">
            <div class="flex items-center">
                <img class="h-6 mt-2" src="../assets/logo.webp" alt="logo">
            </div>

            <div class="flex items-center space-x-3">
                <a target="_blank" href="https://tw.hieuhc.io.vn" class="text-gray-900 transition-colors duration-300 hover:text-primary" aria-label="Github">
                    TailwindCSS Cheet Sheet
                </a>
            </div>
        </nav>
        
        <div class="relative">
            <img class=" z-10 absolute h-[32rem] 2xl:h-[45rem] w-full object-cover" src="../assets/header.webp" alt="header image ">

            <div class=" flex items-center relative z-20 h-[32rem] 2xl:h-[45rem] container mx-auto px-4 ">
                <div class="text-white ">
                    <p class="font-bold tracking-wide uppercase ">OPEN SOURCE TOOL</p>

                    <h1 class="mt-3 text-4xl font-bold ">Tailwind CSS Gradient Generator</h1>

                    <p class="max-w-lg mt-4 ">Mix Tailwind CSS Colors and generate stunning text and background gradients or use our ready-made gradients to create remarkable designs.</p>
                
                    <a href="#generator" class="inline-block px-6 py-3 mt-6 font-medium transition-colors duration-300 bg-gray-900 rounded-lg hover:bg-gray-800">
                        Generate
                    </a>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
import GithubStars from "./GithubStars.vue";

export default {
    name: 'Header',

    components: { GithubStars }
}
</script>