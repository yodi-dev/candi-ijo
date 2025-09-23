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

    <!-- Image -->
    <img src="/images/candi-ijo-4.webp" alt="Candi Ijo Menyapa"
        class="w-full h-[400px] md:h-[500px] lg:h-[600px] object-cover my-12" />

    <section class="max-w-6xl mx-auto px-6 md:px-12 lg:px-24 py-16">

        <!-- Text -->
        <div>
            <h2 class="text-3xl md:text-4xl font-semibold mb-6">Candi Ijo Menyapa</h2>
            <p class="text-gray-700 leading-relaxed space-y-4">
                Dengan penuh rasa hormat, kami mengundang Anda untuk menelusuri salah satu warisan bersejarah
                paling berharga di Daerah Istimewa Yogyakarta. Terletak di ketinggian sekitar 375 meter di atas
                permukaan laut,
                Candi Ijo dikenal sebagai kompleks percandian tertinggi di Yogyakarta yang menyajikan pemandangan megah
                sekaligus kisah peradaban yang agung.
            </p>
            <p class="text-gray-700 leading-relaxed mt-4">
                Candi Ijo dibangun pada masa Mataram Kuno sekitar abad ke-9 Masehi. Setiap batu yang tersusun di sini
                tidak hanya menjadi saksi bisu perkembangan agama Hindu di Nusantara, tetapi juga menyimpan simbol
                kebijaksanaan,
                spiritualitas, dan kehidupan masyarakat pada zamannya.
            </p>
            <p class="text-gray-700 leading-relaxed mt-4">
                Di balik relief-relief dan arsitekturnya, kita dapat menemukan nilai filosofi yang mendalam, sekaligus
                pesan
                tentang harmoni antara manusia, alam, dan Sang Pencipta. Melalui situs ini, kami berkomitmen untuk
                menghadirkan
                informasi yang lengkap, mulai dari sejarah, arsitektur, hingga kegiatan budaya yang dapat Anda saksikan
                di sekitar
                kompleks percandian.
            </p>
            <p class="text-gray-700 leading-relaxed mt-4">
                Lebih dari sekadar destinasi wisata, Candi Ijo adalah ruang belajar, tempat renungan, dan simbol jati
                diri bangsa.
                Kami percaya, dengan mengenal dan mencintai warisan budaya, kita dapat lebih menghargai perjalanan
                panjang sejarah
                Indonesia. Akhir kata, mari bersama menjaga, merawat, dan melestarikan Candi Ijo, agar pesonanya tetap
                abadi untuk
                generasi mendatang.
            </p>
        </div>
    </section>

    <section class="max-w-6xl mx-auto px-6 md:px-12 lg:px-24 py-20">
        <!-- Heading -->
        <h2 class="text-3xl md:text-4xl font-semibold mb-6">Sejarah dan Arsitektur</h2>

        <!-- Description -->
        <p class="text-gray-700 leading-relaxed mb-12">
            Candi Ijo adalah sebuah kompleks candi Hindu yang terletak di perbukitan Hijau di sisi timur Yogyakarta,
            tepatnya di Desa Sambirejo, Prambanan. Berdiri di ketinggian sekitar 375 meter di atas permukaan laut,
            candi ini menjadi salah satu titik tertinggi di wilayah sekitarnya. Dari sini, pengunjung dapat menikmati
            pemandangan luas hamparan sawah, perkotaan, hingga garis cakrawala yang kerap dipenuhi gumapalan awan putih
            seakan berada begitu dekat. Saat pagi atau sore hari, suasana menjadi semakin magis dengan cahaya matahari
            yang
            menyinari setiap sudut bangunan. Selain keindahan alamnya, Candi Ijo juga menyimpan nilai sejarah dan
            arsitektur
            khas abad ke-9, menjadikannya destinasi yang memadukan pesona alam dan warisan budaya.
            <span class="italic">Baca selengkapnya…</span>
        </p>

        <!-- Card Grid -->
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 mb-12">
            <!-- Card -->
            <div
                class="group bg-white rounded-xl shadow-md hover:shadow-xl transition-all duration-300 overflow-hidden hover:-translate-y-2">
                <img src="/images/candi-ijo-7.webp" alt="Sejarah"
                    class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-500">
                <div class="p-4">
                    <h3 class="font-semibold mb-2 text-gray-800">Sejarah</h3>
                    <p class="text-sm text-gray-600">Di atas punggung Bukit Ijo yang tinggi, berdirilah Candi Ijo</p>
                </div>
            </div>

            <div
                class="group bg-white rounded-xl shadow-md hover:shadow-xl transition-all duration-300 overflow-hidden hover:-translate-y-2">
                <img src="/images/candi-ijo-6.webp" alt="Arsitektur"
                    class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-500">
                <div class="p-4">
                    <h3 class="font-semibold mb-2 text-gray-800">Arsitektur</h3>
                    <p class="text-sm text-gray-600">Di atas punggung Bukit Ijo yang tinggi, berdirilah Candi Ijo</p>
                </div>
            </div>

            <div
                class="group bg-white rounded-xl shadow-md hover:shadow-xl transition-all duration-300 overflow-hidden hover:-translate-y-2">
                <img src="/images/hero-candi-ijo.webp" alt="Panduan Wisata"
                    class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-500">
                <div class="p-4">
                    <h3 class="font-semibold mb-2 text-gray-800">Panduan Wisata</h3>
                    <p class="text-sm text-gray-600">Di atas punggung Bukit Ijo yang tinggi, berdirilah Candi Ijo</p>
                </div>
            </div>

            <div
                class="group bg-white rounded-xl shadow-md hover:shadow-xl transition-all duration-300 overflow-hidden hover:-translate-y-2">
                <img src="/images/candi-ijo-5.webp" alt="Event"
                    class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-500">
                <div class="p-4">
                    <h3 class="font-semibold mb-2 text-gray-800">Event</h3>
                    <p class="text-sm text-gray-600">Di atas punggung Bukit Ijo yang tinggi, berdirilah Candi Ijo</p>
                </div>
            </div>
        </div>

        <!-- CTA Button -->
        <div class="text-center">
            <a href="#jelajahi"
                class="inline-block bg-yellow-400 hover:bg-yellow-500 text-black font-semibold py-2 italic px-8 rounded-full shadow-md hover:shadow-lg transition">
                Yuk Jelajahi
            </a>
        </div>
    </section>

    <h2 class="text-3xl md:text-4xl font-semibold ms-6 md:ms-36 mt-12">Candi Diatas Awan</h2>
    <section class="max-w-7xl mx-auto py-20 grid grid-cols-1 md:grid-cols-5 gap-12 items-start">
        <!-- Left Content -->
        <div class="col-span-3">
            <!-- Image -->
            <img src="/images/candi-ijo-2.webp" alt="Candi Ijo Menyapa" class="w-full md:rounded-r-xl object-cover" />
            <p class="text-gray-700 leading-relaxed mt-16 px-6 md:ms-36">
                Candi Ijo adalah sebuah kompleks candi Hindu yang terletak di perbukitan hijau di sisi timur Yogyakarta,
                tepatnya di Desa Sambirejo, Prambanan. Berdiri di ketinggian sekitar 375 meter di atas permukaan laut,
                candi ini menjadi salah satu titik tertinggi di wilayah sekitarnya. Dari sini, pengunjung dapat
                menikmati
                pemandangan luas hamparan sawah, perbukitan, hingga garis cakrawala yang kerap dipenuhi gumpalan awan
                putih
                seakan berada begitu dekat. Saat pagi atau sore hari, suasana menjadi semakin magis dengan cahaya
                matahari
                yang berpadu dengan udara sejuk pegunungan. Selain keindahan alamnya, Candi Ijo juga menyimpan nilai
                sejarah
                dan arsitektur khas abad ke-9, menjadikannya destinasi yang memadukan pesona alam dan warisan budaya.
            </p>
        </div>

        <!-- Right Content -->
        <div class="space-y-12 col-span-2 px-6 md:pe-36">
            <!-- Card 1 -->
            <div class="flex items-start gap-4">
                <img src="/images/candi-di-atas.webp" alt="Candi Ijo"
                    class="w-40 h-40 rounded-xl object-cover shrink-0">
                <div>
                    <h3 class="font-semibold text-md mb-1">Candi Diatas Awan</h3>
                    <p class="text-sm text-gray-600">
                        Di atas punggung Bukit Ijo yang tinggi, berdirilah Candi Ijo, salah satu candi Hindu tertua di
                        Yogyakarta.
                    </p>
                </div>
            </div>

            <!-- Card 2 -->
            <div class="flex items-start gap-4">
                <img src="/images/candi-ijo-3.webp" alt="Candi Ijo" class="w-40 h-40 rounded-xl object-cover shrink-0">
                <div>
                    <h3 class="font-semibold text-md mb-1">Candi Diatas Awan</h3>
                    <p class="text-sm text-gray-600">
                        Di atas punggung Bukit Ijo yang tinggi, berdirilah Candi Ijo, salah satu candi Hindu tertua di
                        Yogyakarta.
                    </p>
                </div>
            </div>

            <!-- Card 3 -->
            <div class="flex items-start gap-4">
                <img src="/images/hero-candi-ijo.webp" alt="Candi Ijo"
                    class="w-40 h-40 rounded-xl object-cover shrink-0">
                <div>
                    <h3 class="font-semibold text-md mb-1">Candi Diatas Awan</h3>
                    <p class="text-sm text-gray-600">
                        Di atas punggung Bukit Ijo yang tinggi, berdirilah Candi Ijo, salah satu candi Hindu tertua di
                        Yogyakarta.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <h2 class="text-3xl md:text-4xl font-semibold ms-6 md:ms-36 mt-12">Sunset di Candi Ijo</h2>
    <section class="max-w-7xl mx-auto py-20 grid grid-cols-1 md:grid-cols-11 gap-8 items-start">
        <!-- Left Content -->
        <div class="col-span-4">
            <p class="text-gray-700 leading-relaxed px-6 md:ms-36">
                Candi Ijo adalah sebuah kompleks candi Hindu yang terletak di perbukitan hijau di sisi timur Yogyakarta,
                tepatnya di Desa Sambirejo, Prambanan. Berdiri di ketinggian sekitar 375 meter di atas permukaan laut,
                candi ini menjadi salah satu titik tertinggi di wilayah sekitarnya. Dari sini, pengunjung dapat
                menikmati
                pemandangan luas hamparan sawah, perbukitan, hingga garis cakrawala yang kerap dipenuhi gumpalan awan
                putih
                seakan berada begitu dekat. Saat pagi atau sore hari, suasana menjadi semakin magis dengan cahaya
                matahari
                yang berpadu dengan udara sejuk pegunungan. Selain keindahan alamnya, Candi Ijo juga menyimpan nilai
                sejarah
                dan arsitektur khas abad ke-9, menjadikannya destinasi yang memadukan pesona alam dan warisan budaya.
            </p>
        </div>

        <div class="col-span-2 px-6 md:px-0">
            <img src="/images/sunset-1.webp" alt="Candi Ijo Menyapa" class="w-52 h-52 rounded-xl object-cover" />
            <!-- Image -->
            <!-- CTA Button -->
            <div class="text-center mt-32">
                <a href="#jelajahi"
                    class="inline-block bg-yellow-400 hover:bg-yellow-500 text-black font-semibold italic py-2 px-8 rounded-full shadow-md hover:shadow-lg transition">
                    Yuk Jelajahi
                </a>
            </div>
        </div>

        <!-- Right Content -->
        <div class="col-span-5">
            <img src="/images/sunset.webp" alt="Candi Ijo Menyapa" class="h-screen object-cover md:rounded-l-xl"
                style="object-position: 40% 0;" />
        </div>
    </section>


</template>
