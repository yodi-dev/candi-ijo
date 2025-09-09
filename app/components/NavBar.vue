<template>
    <nav class="fixed top-0 left-0 right-0 z-50 border-b border-white/10 bg-slate-900/50">
        <div class="mx-auto max-w-7xl px-6 lg:px-12 py-3 flex items-center justify-between">

            <!-- Logo -->
            <NuxtLink to="/">
                <img src="~/assets/images/logo.png" alt="Logo" class="w-10 h-auto rounded-sm" />
            </NuxtLink>

            <!-- Links (Desktop) -->
            <ul class="hidden md:flex flex-wrap gap-6 text-sm">
                <li v-for="l in links" :key="l.to">
                    <NuxtLink :to="l.to" :class="[
                        'px-2 py-1 rounded transition-colors',
                        route.path === l.to
                            ? 'text-green-400 font-medium'
                            : 'text-gray-200 hover:text-white hover:bg-white/10'
                    ]">
                        {{ l.label }}
                    </NuxtLink>
                </li>
            </ul>

            <!-- Right: Flag (desktop) / Hamburger (mobile) -->
            <div class="flex items-center">
                <!-- Flag -->
                <img src="~/assets/images/id-flag.png" alt="ID Flag"
                    class="hidden md:block h-5 w-auto rounded-sm shadow" />

                <!-- Hamburger (mobile) -->
                <button @click="isOpen = !isOpen"
                    class="md:hidden ml-2 text-gray-200 hover:text-white focus:outline-none">
                    <svg v-if="!isOpen" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none"
                        viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                    <svg v-else xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24"
                        stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M6 18L18 6M6 6l12 12" />
                    </svg>
                </button>
            </div>
        </div>

        <!-- Mobile Menu -->
        <div v-if="isOpen" class="md:hidden bg-slate-900/95 border-t border-white/10">
            <ul class="flex flex-col px-6 py-4 gap-3 text-sm">
                <li v-for="l in links" :key="l.to">
                    <NuxtLink :to="l.to" @click="isOpen = false" :class="[
                        'block px-2 py-2 rounded transition-colors',
                        route.path === l.to
                            ? 'text-green-400 font-semibold'
                            : 'text-gray-200 hover:text-white hover:bg-white/10'
                    ]">
                        {{ l.label }}
                    </NuxtLink>
                </li>
                <!-- Flag in mobile menu -->
                <li class="pt-2">
                    <img src="~/assets/images/id-flag.png" alt="ID Flag" class="h-5 w-auto rounded-sm shadow" />
                </li>
            </ul>
        </div>
    </nav>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const route = useRoute()
const isOpen = ref(false)

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