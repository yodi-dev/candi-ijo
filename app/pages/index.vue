<script setup>
const title = 'Candi Ijo — Candi Tertinggi di Yogyakarta'
const subtitle = 'Sekilas pengantar dan highlight konten situs.'
</script>

<template>
    <PageHero :title="title" :subtitle="subtitle">
        <NuxtLink to="/panduan-wisata" class="inline-block rounded bg-green-700 px-4 py-2 text-white hover:opacity-90">
            Jelajahi Sekarang
        </NuxtLink>
    </PageHero>

    <section class="px-4 pb-12">
        <div class="mx-auto max-w-5xl grid gap-6 md:grid-cols-3">
            <div class="rounded-lg border p-4">
                <h3 class="font-medium">Sejarah</h3>
                <p class="text-sm text-gray-600 mt-1">Asal-usul dan periodisasi.</p>
                <NuxtLink to="/sejarah" class="text-green-700 text-sm mt-2 inline-block">Lihat →</NuxtLink>
            </div>
            <div class="rounded-lg border p-4">
                <h3 class="font-medium">Arsitektur</h3>
                <p class="text-sm text-gray-600 mt-1">Struktur, relief, dan simbol.</p>
                <NuxtLink to="/arsitektur" class="text-green-700 text-sm mt-2 inline-block">Lihat →</NuxtLink>
            </div>
            <div class="rounded-lg border p-4">
                <h3 class="font-medium">Sunset</h3>
                <p class="text-sm text-gray-600 mt-1">Waktu terbaik & spot foto.</p>
                <NuxtLink to="/sunset" class="text-green-700 text-sm mt-2 inline-block">Lihat →</NuxtLink>
            </div>
        </div>
    </section>
</template>
