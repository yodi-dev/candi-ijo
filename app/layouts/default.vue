<template>
    <div class="min-h-dvh flex flex-col">
        <NavBar />
        <main class="flex-1">
            <slot />
        </main>
        <Footer>
            <div class="mx-auto max-w-7xl px-4 py-6 text-sm text-gray-600">
                © 2025 Candi Ijo. All Rights Reserved.
            </div>
        </Footer>
    </div>
</template>

<script setup>
import NavBar from '~/components/NavBar.vue'
</script>
