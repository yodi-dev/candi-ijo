<script setup>
const title = 'Candi Ijo — Candi Tertinggi di Yogyakarta'
const heroBg = 'images/hero-candi-ijo.webp'
</script>

<template>
    <PageHero :title="title" :background="heroBg">
        <NuxtLink to="/panduan-wisata"
            class="inline-block rounded-full bg-white/60 px-6 py-2 text-black hover:bg-white/90 transition">
            Jelajahi Sekarang
        </NuxtLink>
    </PageHero>

    <section class="max-w-7xl mt-12 mx-auto px-6 lg:px-36 py-16 grid grid-cols-1 md:grid-cols-3 gap-12 items-center">
        <!-- Text (1/3) -->
        <div class="md:col-span-1">
            <h2 class="text-4xl font-medium mb-8">Selamat Datang <br> di Candi Ijo</h2>
            <p class="text-gray-700 leading-relaxed">
                Di puncak perbukitan timur Yogyakarta, berdiri megah Candi Ijo – sebuah kompleks percandian
                Hindu dari abad ke-9 yang menyimpan jejak peradaban Mataram Kuno. Dari ketinggian ini, mata Anda
                akan dimanjakan oleh bentangan lanskap yang tiada duanya: sawah-sawah hijau yang membentang luas,
                bukit-bukit yang berlapis indah, hingga garis laut selatan yang terlihat samar di kejauhan.
                Suasana sunyi berpadu dengan hembusan angin perbukitan menghadirkan ketenangan yang sulit dijumpai
                di tempat lain. Candi Ijo bukan sekadar situs bersejarah, melainkan ruang di mana alam, budaya,
                dan spiritualitas bertemu, mengajak setiap pengunjung untuk merenung, belajar, sekaligus merasakan
                pesona Yogyakarta dari sudut pandang tertinggi.
            </p>
        </div>

        <!-- Images (2/3) -->
        <div class="md:col-span-2 grid grid-cols-2 h-full">
            <!-- Gambar besar kiri -->
            <img src="/images/candi-ijo-2.webp" alt="Candi Ijo 1"
                class="my-auto ms-12 rounded-3xl object-cover w-60 h-1/2" />

            <!-- Dua gambar kanan -->
            <div class="grid grid-rows-2 gap-8 h-full">
                <img src="/images/candi-ijo-1.webp" alt="Candi Ijo 2" class="rounded-3xl object-cover w-60 h-full"
                    style="object-position: 85% 0;" />
                <img src="/images/candi-ijo-3.webp" alt="Candi Ijo 3" class="rounded-3xl object-cover w-60 h-full" />
            </div>
        </div>
    </section>

</template>
