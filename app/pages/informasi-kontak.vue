<script setup>
const title = 'Informasi & Kontak'
const subtitle = 'Informasi umum, alamat, dan formulir kontak.'
</script>

<template>
    <PageHero :title="title" :subtitle="subtitle" />
    <section class="px-4 pb-12">
        <div class="mx-auto max-w-5xl grid gap-6 md:grid-cols-2">
            <div class="rounded-lg border p-4">
                <h3 class="font-medium">Informasi Umum</h3>
                <ul class="mt-2 text-sm text-gray-700 space-y-1">
                    <li><strong>Alamat:</strong> …</li>
                    <li><strong>Jam Buka:</strong> …</li>
                    <li><strong>Media Sosial:</strong> …</li>
                </ul>
            </div>
            <form class="rounded-lg border p-4 space-y-3">
                <div>
                    <label class="block text-sm mb-1">Nama</label>
                    <input class="w-full rounded border px-3 py-2" />
                </div>
                <div>
                    <label class="block text-sm mb-1">Email</label>
                    <input type="email" class="w-full rounded border px-3 py-2" />
                </div>
                <div>
                    <label class="block text-sm mb-1">Pesan</label>
                    <textarea rows="4" class="w-full rounded border px-3 py-2" />
                </div>
                <button type="button" class="rounded bg-green-700 px-4 py-2 text-white hover:opacity-90">
                    Kirim
                </button>
            </form>
        </div>
    </section>
</template>
