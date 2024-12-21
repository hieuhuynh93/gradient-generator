<template>
    <div class="bg-gray-100">
        <div class="container flex flex-col items-center px-4 py-6 mx-auto space-y-6 lg:space-y-0 lg:flex-row lg:justify-between">
            <div class="w-48 text-gray-700">
                <img class="object-cover object-left h-6" src="../assets/logo.svg" alt="Tailwindcomponents logo">
            </div>

            <p class="text-sm text-center text-gray-500">&copy; {{ new Date().getFullYear() }} <a target="_blank" href="https://tailwindcomponents.com" class="hover:text-primary">tailwindcomponents</a> designed by <a target="_blank" href="https://www.creative-tim.com/" class="hover:text-primary">Creative Tim</a>, all rights reserved. Made with ❤️ for a better web.</p>


        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer',
}
</script>