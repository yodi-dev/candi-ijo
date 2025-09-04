<template>
    <section class="px-4 py-10 md:py-14">
        <div class="mx-auto max-w-5xl">
            <h1 class="text-3xl md:text-4xl font-semibold tracking-tight">
                {{ title }}
            </h1>
            <p v-if="subtitle" class="mt-3 text-gray-600 max-w-3xl">
                {{ subtitle }}
            </p>
            <div class="mt-6">
                <slot />
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
const props = defineProps<{
    title: string
    subtitle?: string
}>()
</script>
