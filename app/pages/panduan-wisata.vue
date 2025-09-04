<script setup>
const title = 'Panduan Wisata'
const subtitle = 'Lokasi, rute, tiket, jam buka, etika berkunjung.'
</script>

<template>
    <PageHero :title="title" :subtitle="subtitle" />
    <section class="px-4 pb-12">
        <div class="mx-auto max-w-5xl grid gap-4 md:grid-cols-3">
            <div class="rounded-lg border p-4">
                <h3 class="font-medium">Lokasi & Akses</h3>
                <p class="text-sm text-gray-600 mt-1">Alamat & rute.</p>
            </div>
            <div class="rounded-lg border p-4">
                <h3 class="font-medium">Tiket & Jam Buka</h3>
                <p class="text-sm text-gray-600 mt-1">Harga & jadwal.</p>
            </div>
            <div class="rounded-lg border p-4">
                <h3 class="font-medium">Etika & Tips</h3>
                <p class="text-sm text-gray-600 mt-1">Hal yang perlu diperhatikan.</p>
            </div>
        </div>
    </section>
</template>
