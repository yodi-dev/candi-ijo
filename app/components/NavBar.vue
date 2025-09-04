<template>
    <nav class="fixed top-0 left-0 right-0 z-50 border-b border-white/10 bg-slate-900/50">
        <div class="mx-auto max-w-7xl px-6 lg:px-12 py-3 flex items-center justify-between">

            <!-- Logo -->
            <NuxtLink to="/">
                <img src="assets/images/logo.png" alt="ID Flag" class="w-10 h-auto rounded-sm" />
            </NuxtLink>

            <!-- Links -->
            <ul class="hidden md:flex flex-wrap gap-6 text-sm">
                <li v-for="l in links" :key="l.to">
                    <NuxtLink :to="l.to" :class="[
                        'px-2 py-1 rounded transition-colors',
                        route.path === l.to
                            ? 'text-green-400 font-semibold'
                            : 'text-gray-200 hover:text-white hover:bg-white/10'
                    ]">
                        {{ l.label }}
                    </NuxtLink>
                </li>
            </ul>

            <!-- Bendera -->
            <div class="flex items-center">
                <img src="assets/images/id-flag.png" alt="ID Flag" class="h-5 w-auto rounded-sm shadow" />
            </div>
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
    { to: '/mitos-fakta-rakyat', label: 'Cerita' },
    { to: '/sunset', label: 'Sunset' },
    { to: '/informasi-kontak', label: 'Informasi' },
]
</script>
