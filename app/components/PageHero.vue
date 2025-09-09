<template>
    <section class="relative h-[80vh] flex items-center justify-center text-center text-white">
        <!-- Background -->
        <div class="absolute inset-0 bg-cover bg-center" :style="{ backgroundImage: `url(${background})` }">
            <!-- Overlay -->
            <!-- <div class="absolute inset-0 bg-black/50"></div> -->
        </div>

        <!-- Content -->
        <div class="relative px-4">
            <h1 class="text-3xl md:text-4xl font-medium drop-shadow mt-24 mb-12">{{ title }}</h1>
            <p class="mt-4 max-w-2xl mx-auto text-base md:text-lg text-gray-200">{{ subtitle }}</p>
            <div class="mt-6">
                <slot />
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
defineProps<{
    title: string
    subtitle?: string
    background: string // kirim path atau import di parent
}>()
</script>
