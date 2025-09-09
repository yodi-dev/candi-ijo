<template>
    <footer class="bg-white text-gray-800">
        <div class="mx-auto max-w-7xl px-6 lg:px-40 py-8 space-y-12">

            <!-- Baris pertama -->
            <div class="flex flex-col md:flex-row items-center justify-between border-b border-black">
                <!-- Logo + Nama -->
                <div class="flex items-center gap-4">
                    <svg height="150" viewBox="0 0 252 252" fill="none" xmlns="http://www.w3.org/2000/svg"
                        xmlns:xlink="http://www.w3.org/1999/xlink">
                        <rect width="252" height="252" fill="url(#pattern0_1196_11)" />
                        <defs>
                            <pattern id="pattern0_1196_11" patternContentUnits="objectBoundingBox" width="1" height="1">
                                <use xlink:href="#image0_1196_11" transform="scale(0.00277778)" />
                            </pattern>
                            <image id="image0_1196_11" width="360" height="360" preserveAspectRatio="none"
                                xlink:href="data:image/png;base64,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" />
                        </defs>
                    </svg>
                    <div class="flex items-center">
                        <span class="border-l border-black h-10 ms-4 me-7"></span>
                        <h2 class="text-xl font-semibold ps-4">Candi Ijo</h2>
                    </div>
                </div>

                <!-- Sosmed -->
                <div class="flex gap-4 text-xl">
                    <a href="#" class="text-pink-500"><i class="ri-instagram-fill"></i></a>
                    <a href="#" class="text-blue-600"><i class="ri-facebook-circle-fill"></i></a>
                    <a href="#" class="text-red-500"><i class="ri-youtube-fill"></i></a>
                    <a href="#" class="text-black"><i class="ri-tiktok-fill"></i></a>
                    <a href="#" class="text-gray-700"><i class="ri-twitter-x-fill"></i></a>
                </div>
            </div>

            <!-- Baris kedua -->
            <nav class="pb-16">
                <ul class="flex flex-wrap justify-center gap-8 border-none text-sm">
                    <li v-for="l in links" :key="l.to">
                        <NuxtLink :to="l.to" class="hover:underline">
                            {{ l.label }}
                        </NuxtLink>
                    </li>
                </ul>
            </nav>

            <!-- Baris ketiga -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-sm border-b border-black pb-8">
                <div>
                    <h3 class="font-semibold mb-1">Kontak Kami</h3>
                    <p>candiijo@gmail.com</p>
                </div>
                <div>
                    <h3 class="font-semibold mb-1">Alamat Kantor Pusat</h3>
                    <p>Dusun Groyokan, Desa Sambirejo, Kecamatan Prambanan, Kabupaten Sleman, Daerah Istimewa
                        Yogyakarta.</p>
                </div>
                <div>
                    <h3 class="font-semibold mb-1">Alamat Kantor Perwakilan</h3>
                    <p>Groyokan Jl. Candi Ijo, Klikis, Sambirejo, Kec. Prambanan, Kabupaten Sleman, Daerah Istimewa
                        Yogyakarta 55572</p>
                </div>
            </div>
        </div>

        <!-- Baris terakhir -->
        <div class="bg-gray-400 text-center py-3 text-sm text-white">
            PT Taman Wisata Candi Ijo ©2025. All Rights Reserved
        </div>
    </footer>
</template>

<script setup lang="ts">
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
