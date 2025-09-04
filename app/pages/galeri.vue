<script setup>
const title = 'Galeri'
const subtitle = 'Kumpulan foto resmi & dokumentasi.'
</script>

<template>
    <PageHero :title="title" :subtitle="subtitle" />
    <section class="px-4 pb-12">
        <div class="mx-auto max-w-6xl grid grid-cols-2 md:grid-cols-3 gap-3">
            <div class="aspect-[4/3] rounded-lg bg-gray-100"></div>
            <div class="aspect-[4/3] rounded-lg bg-gray-100"></div>
            <div class="aspect-[4/3] rounded-lg bg-gray-100"></div>
            <div class="aspect-[4/3] rounded-lg bg-gray-100"></div>
            <div class="aspect-[4/3] rounded-lg bg-gray-100"></div>
            <div class="aspect-[4/3] rounded-lg bg-gray-100"></div>
        </div>
    </section>
</template>
