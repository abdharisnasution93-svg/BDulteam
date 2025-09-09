<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BDulteam - Jasa Profesional Terpercaya</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117;
            color: #f0f6fc;
        }
        .text-gradient {
            background: linear-gradient(90deg, #38bdf8, #8b5cf6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .hero-bg {
            background-image: url('https://placehold.co/1920x1080/0d1117/2c333b?text=BDul+Team');
            background-size: cover;
            background-position: center;
            position: relative;
            z-index: 1;
        }
        .hero-bg::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            z-index: -1;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header -->
    <header class="sticky top-0 z-50 bg-[#0d1117]/80 backdrop-blur-md border-b border-gray-700">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#home" class="text-2xl font-bold text-gray-100">BDul <span class="text-blue-400">Team</span></a>
            <div class="hidden md:flex space-x-8 items-center">
                <a href="#layanan" class="text-gray-300 hover:text-blue-400 transition-colors">Layanan</a>
                <a href="#tentang" class="text-gray-300 hover:text-blue-400 transition-colors">Tentang Kami</a>
                <a href="#kontak" class="text-gray-300 hover:text-blue-400 transition-colors">Kontak</a>
                <a href="https://wa.me/628116190093" target="_blank" class="flex items-center space-x-2 bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-4 rounded-full transition-transform transform hover:scale-105">
                    <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M12 2C6.477 2 2 6.477 2 12c0 2.23.72 4.318 1.956 6.007L2 22l4.137-1.115A9.976 9.976 0 0012 22c5.523 0 10-4.477 10-10S17.523 2 12 2zm2.062 14.156c-.347.19-.74.305-1.133.305-.407 0-.814-.115-1.16-.322-.505-.262-.843-.722-1.026-1.22-.182-.498-.262-1.02-.23-1.542l.067-.935c.033-.464.21-.86.533-1.144.323-.284.72-.43 1.14-.413.433.017.85.163 1.18.43.33.267.545.62.647 1.05.102.43.12 1.01-.12 1.542-.24.532-.612.982-1.096 1.353-.484.37-.99.55-1.52.533-.53 0-1.04-.18-1.524-.532-.483-.35-.855-.78-1.095-1.29-.24-.51-.302-1.05-.18-1.61.12-.56.417-1.107.893-1.48.477-.373 1.03-.564 1.597-.564.567 0 1.13.19 1.63.564.5.373.873.86.993 1.48.12.62.06 1.25-.18 1.832-.24.582-.577 1.13-.993 1.48z"/>
                    </svg>
                    Hubungi Kami
                </a>
            </div>
            <div class="md:hidden">
                <button id="menu-button" class="text-gray-300 focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                    </svg>
                </button>
            </div>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-[#0d1117] px-6 py-4 border-t border-gray-700">
            <a href="#layanan" class="block py-2 text-gray-300 hover:text-blue-400 transition-colors">Layanan</a>
            <a href="#tentang" class="block py-2 text-gray-300 hover:text-blue-400 transition-colors">Tentang Kami</a>
            <a href="#kontak" class="block py-2 text-gray-300 hover:text-blue-400 transition-colors">Kontak</a>
            <a href="https://wa.me/628116190093" target="_blank" class="mt-4 block text-center bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-4 rounded-full transition-transform transform hover:scale-105">Hubungi Kami</a>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="home" class="hero-bg h-screen flex flex-col justify-center items-center text-center px-6">
            <h1 class="text-4xl sm:text-5xl md:text-6xl font-bold text-gray-100 leading-tight mb-4">
                <span class="text-gradient">BDul Team</span><br> Solusi Profesional Terpercaya
            </h1>
            <p class="text-lg md:text-xl text-gray-300 max-w-2xl mb-8">
                Kami menyediakan berbagai jasa profesional untuk kebutuhan personal, bisnis, dan korporat dengan integritas tinggi.
            </p>
            <div class="relative w-full max-w-2xl h-64 md:h-96 bg-gray-900 rounded-3xl overflow-hidden shadow-lg">
                <img src="https://placehold.co/1920x1080/1a202c/f0f6fc?text=Video+Pendek+Tentang+Layanan" alt="Placeholder video BDul Team" class="w-full h-full object-cover">
                <div class="absolute inset-0 flex items-center justify-center">
                    <button class="w-16 h-16 bg-blue-600 text-white rounded-full flex items-center justify-center hover:scale-110 transition-transform">
                        <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M8 5v14l11-7z"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </section>

        <!-- Layanan Section -->
        <section id="layanan" class="py-16 bg-[#1a202c]">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Layanan Kami</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

                    <!-- Jasa Pencarian & Verifikasi -->
                    <div class="bg-[#2c333b] p-8 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                        <div class="mb-4">
                            <svg class="w-12 h-12 text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Pencarian & Verifikasi Data</h3>
                        <p class="text-gray-400">Jasa pencarian kebenaran dan keaslian data untuk keperluan inspeksi, audit, dan lainnya. Termasuk pencarian orang secara spesifik dengan detail lengkap.</p>
                    </div>

                    <!-- Jasa Pribadi & Perusahaan -->
                    <div class="bg-[#2c333b] p-8 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                        <div class="mb-4">
                            <svg class="w-12 h-12 text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Jasa Asisten & Profesi Pribadi</h3>
                        <p class="text-gray-400">Menyediakan asisten pribadi, supir, pengawal, akuntan, dan pengacara pribadi yang profesional dan terpercaya.</p>
                    </div>

                    <!-- Jasa Legalitas Perusahaan -->
                    <div class="bg-[#2c333b] p-8 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                        <div class="mb-4">
                            <svg class="w-12 h-12 text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Pembuatan Legalitas Perusahaan</h3>
                        <p class="text-gray-400">Jasa pembuatan legalitas untuk CV, PT, UD, Yayasan, perkumpulan, dan badan usaha lainnya.</p>
                    </div>

                    <!-- Jasa IT & Teknologi -->
                    <div class="bg-[#2c333b] p-8 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                        <div class="mb-4">
                            <svg class="w-12 h-12 text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Jasa IT & Pembuatan Website</h3>
                        <p class="text-gray-400">Layanan teknisi komputer, laptop, printer, networking, dan software khusus (SAP, ERP, Keuangan, dll), serta jasa pembuatan website profesional.</p>
                    </div>

                    <!-- Jasa Pemetaan -->
                    <div class="bg-[#2c333b] p-8 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                        <div class="mb-4">
                            <svg class="w-12 h-12 text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 20l-5.447-2.724A1 1 0 013 16.382V5.618a1 1 0 01.553-.894L9 2m7 18l5.447-2.724A1 1 0 0021 16.382V5.618a1 1 0 00-.553-.894L15 2m-7 18v-5m0 0a2 2 0 100-4 2 2 0 000 4zm-3.5 0h7A3.5 3.5 0 0013.5 15h0a3.5 3.5 0 00-3.5-3.5zm7 0h3.5a3.5 3.5 0 010 7h-3.5m-7-7h3.5m0 0a3.5 3.5 0 010-7h3.5a3.5 3.5 0 010 7"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Jasa Pemetaan & Surveyor</h3>
                        <p class="text-gray-400">Melayani pemetaan dan survei untuk perusahaan kelapa sawit, tambang, forestry, pertanian, dan pengukuran tanah dengan GPS atau drone.</p>
                    </div>
                    
                    <!-- Jasa Pembinaan & Lainnya -->
                    <div class="bg-[#2c333b] p-8 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                        <div class="mb-4">
                            <svg class="w-12 h-12 text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 10H2v2h12v-2zm0 4H2v2h12v-2zm-4-8H2v2h8V6zm4 0h10v2H14V6zm-4 4h10v2H10v-2zm0 4h10v2H10v-2z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Layanan Lainnya</h3>
                        <p class="text-gray-400">Jasa pembuatan RAB, data research, pembinaan jasmani & mental calon siswa TNI/Polri, serta jasa traveling.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Tentang Kami Section -->
        <section id="tentang" class="py-16 bg-[#0d1117]">
            <div class="container mx-auto px-6 text-center max-w-4xl">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Tentang BDul Team</h2>
                <p class="text-lg text-gray-400 leading-relaxed">
                    **BDul Team** adalah tim profesional yang berdedikasi untuk menyediakan solusi terbaik bagi setiap klien. Dengan fokus pada integritas, keahlian, dan kerahasiaan, kami berkomitmen untuk membantu Anda mencapai tujuan, baik untuk kebutuhan personal maupun bisnis. Kepercayaan Anda adalah prioritas utama kami.
                </p>
                <div class="mt-8 flex justify-center">
                    <img src="https://placehold.co/800x400/1a202c/f0f6fc?text=Tim+BDul+Team" alt="Gambar tim BDul Team" class="rounded-xl shadow-lg">
                </div>
            </div>
        </section>

        <!-- Kontak Section -->
        <section id="kontak" class="py-16 bg-[#1a202c]">
            <div class="container mx-auto px-6 text-center max-w-2xl">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Hubungi Kami</h2>
                <p class="text-lg text-gray-400 mb-8">
                    Mari wujudkan kebutuhan Anda bersama kami. Hubungi kami sekarang untuk konsultasi gratis!
                </p>
                <div class="flex flex-col items-center space-y-4">
                    <a href="https://wa.me/628116190093" target="_blank" class="w-full sm:w-auto flex items-center justify-center space-x-2 bg-green-500 hover:bg-green-600 text-white font-medium py-3 px-8 rounded-full shadow-lg transition-transform transform hover:scale-105">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2C6.477 2 2 6.477 2 12c0 2.23.72 4.318 1.956 6.007L2 22l4.137-1.115A9.976 9.976 0 0012 22c5.523 0 10-4.477 10-10S17.523 2 12 2zm2.062 14.156c-.347.19-.74.305-1.133.305-.407 0-.814-.115-1.16-.322-.505-.262-.843-.722-1.026-1.22-.182-.498-.262-1.02-.23-1.542l.067-.935c.033-.464.21-.86.533-1.144.323-.284.72-.43 1.14-.413.433.017.85.163 1.18.43.33.267.545.62.647 1.05.102.43.12 1.01-.12 1.542-.24.532-.612.982-1.096 1.353-.484.37-.99.55-1.52.533-.53 0-1.04-.18-1.524-.532-.483-.35-.855-.78-1.095-1.29-.24-.51-.302-1.05-.18-1.61.12-.56.417-1.107.893-1.48.477-.373 1.03-.564 1.597-.564.567 0 1.13.19 1.63.564.5.373.873.86.993 1.48.12.62.06 1.25-.18 1.832-.24.582-.577 1.13-.993 1.48z"/>
                        </svg>
                        Hubungi via WhatsApp (+62 811 6190 093)
                    </a>
                    <a href="mailto:bdulteamsiluman93@gmail.com" class="text-blue-400 hover:underline transition-colors">bdulteamsiluman93@gmail.com</a>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-[#2c333b] py-8 text-center border-t border-gray-700">
        <div class="container mx-auto px-6">
            <div class="text-gray-400 mb-2">
                &copy; 2023 BDul Team. Semua Hak Cipta Dilindungi.
            </div>
            <div class="flex justify-center space-x-4 text-gray-400">
                <a href="#layanan" class="hover:text-blue-400">Layanan</a>
                <a href="#tentang" class="hover:text-blue-400">Tentang Kami</a>
                <a href="#kontak" class="hover:text-blue-400">Kontak</a>
            </div>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // Smooth scrolling for navigation links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            });

            // Mobile menu toggle
            const menuButton = document.getElementById('menu-button');
            const mobileMenu = document.getElementById('mobile-menu');

            menuButton.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });
        });
    </script>
</body>
</html>
