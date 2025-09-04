<template>
    <nav class="border-b bg-white/80 backdrop-blur">
        <div class="mx-auto max-w-7xl px-4 py-3 flex items-center gap-6">
            <NuxtLink to="/" class="font-semibold">🌿 Candi Ijo</NuxtLink>
            <ul class="flex flex-wrap gap-4 text-sm">
                <li v-for="l in links" :key="l.to">
                    <NuxtLink :to="l.to" :class="[
                        'px-2 py-1 rounded hover:bg-gray-100',
                        route.path === l.to ? 'text-green-700 font-medium' : 'text-gray-700'
                    ]">
                        {{ l.label }}
                    </NuxtLink>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script setup lang="ts">
const route = useRoute()
const links = [
    { to: '/', label: 'Beranda' },
    { to: '/sejarah', label: 'Sejarah' },
    { to: '/arsitektur', label: 'Arsitektur' },
    { to: '/galeri', label: 'Galeri' },
    { to: '/panduan-wisata', label: 'Panduan Wisata' },
    { to: '/mitos-fakta-rakyat', label: 'Mitos & Fakta Rakyat' },
    { to: '/sunset', label: 'Sunset' },
    { to: '/informasi-kontak', label: 'Informasi & Kontak' },
]
</script>
