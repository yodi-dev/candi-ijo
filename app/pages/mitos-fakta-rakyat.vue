<script setup>
const title = 'Mitos & Fakta Rakyat'
const subtitle = 'Cerita rakyat, tafsir simbol, dan klarifikasi.'
</script>

<template>
    <PageHero :title="title" :subtitle="subtitle" />
    <section class="px-4 pb-12">
        <div class="mx-auto max-w-4xl space-y-4">
            <div class="rounded-lg border p-4">
                <h3 class="font-medium">Mitos 1</h3>
                <p class="text-sm text-gray-600 mt-1">Ringkasan…</p>
            </div>
            <div class="rounded-lg border p-4">
                <h3 class="font-medium">Mitos 2</h3>
                <p class="text-sm text-gray-600 mt-1">Ringkasan…</p>
            </div>
        </div>
    </section>
</template>
