<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard Eksekutif - UPT SD Negeri Kalutuk</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome untuk Icon -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Plus Jakarta Sans -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['"Plus Jakarta Sans"', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style>
        .glass-card {
            background: rgba(30, 41, 59, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(51, 65, 85, 0.8);
        }
        .hero-gradient {
            background: linear-gradient(135deg, #1e1b4b 0%, #312e81 50%, #4338ca 100%);
        }
    </style>
</head>
<body class="bg-slate-900 text-slate-100 font-sans antialiased min-h-screen selection:bg-indigo-500 selection:text-white">

    <!-- Top Navigation Bar -->
    <nav class="sticky top-0 z-50 bg-slate-900/80 backdrop-blur-md border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex justify-between items-center">
            <div class="flex items-center space-x-4">
                <div class="relative group">
                    <div class="absolute -inset-0.5 bg-gradient-to-r from-indigo-500 to-cyan-500 rounded-full blur opacity-75 group-hover:opacity-100 transition duration-300"></div>
                    <div class="relative w-12 h-12 rounded-full bg-slate-900 overflow-hidden flex items-center justify-center border-2 border-slate-700">
                        <img src="LOGO KALUTUK.jpeg" alt="Logo UPT SD Negeri Kalutuk" class="w-full h-full object-cover">
                    </div>
                </div>
                <div>
                    <h1 class="text-lg sm:text-xl font-extrabold tracking-tight text-white flex items-center gap-2">
                        UPT SD NEGERI KALUTUK
                        <span class="bg-indigo-500/20 text-indigo-400 text-[10px] font-semibold px-2 py-0.5 rounded-full border border-indigo-500/30">Official</span>
                    </h1>
                    <p class="text-xs text-slate-400 font-medium">Kecamatan Cikande, Kabupaten Serang, Banten</p>
                </div>
            </div>
            <div class="hidden md:flex items-center space-x-3 bg-slate-800/60 border border-slate-700/60 px-4 py-2 rounded-2xl">
                <div class="w-8 h-8 rounded-xl bg-indigo-500/20 text-indigo-400 flex items-center justify-center font-bold">
                    <i class="fa-solid fa-user-shield text-sm"></i>
                </div>
                <div class="text-xs">
                    <p class="text-slate-400">Kepala Sekolah</p>
                    <p class="font-bold text-white">Sukma, S.Pd</p>
                </div>
            </div>
        </div>
    </nav>

    <!-- Main Content Container -->
    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8 space-y-8">

        <!-- Hero Banner Section -->
        <section class="relative hero-gradient rounded-3xl p-8 sm:p-12 overflow-hidden shadow-2xl border border-slate-700/50">
            <div class="absolute -right-10 -bottom-10 opacity-10 pointer-events-none">
                <i class="fa-solid fa-graduation-cap text-[280px] text-white"></i>
            </div>
            <div class="absolute top-0 right-1/4 w-96 h-96 bg-indigo-500/10 rounded-full blur-3xl pointer-events-none"></div>
            
            <div class="relative z-10 max-w-2xl space-y-4">
                <div class="inline-flex items-center gap-2 bg-indigo-500/20 border border-indigo-400/30 px-3 py-1 rounded-full text-indigo-300 text-xs font-semibold tracking-wide">
                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                    Sistem Informasi & Manajemen Pendidikan
                </div>
                <h2 class="text-3xl sm:text-5xl font-black tracking-tight text-white leading-tight">
                    Membangun Generasi Unggul & Berkarakter
                </h2>
                <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
                    Selamat datang di pusat data dan informasi resmi UPT SD Negeri Kalutuk. Transparansi informasi akademik, direktori tenaga pendidik, dan dokumentasi sekolah dalam satu genggaman.
                </p>
            </div>
        </section>

        <!-- Stats Grid (Modern Cards with Glow Effects) -->
        <section class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <!-- Card Siswa -->
            <div class="glass-card p-6 rounded-3xl shadow-xl relative overflow-hidden group hover:border-indigo-500/50 transition-all duration-300">
                <div class="absolute top-0 right-0 p-6 opacity-10 group-hover:opacity-20 transition-opacity">
                    <i class="fa-solid fa-user-graduate text-6xl text-blue-400"></i>
                </div>
                <div class="flex items-center space-x-4">
                    <div class="w-14 h-14 bg-blue-500/10 border border-blue-500/20 text-blue-400 rounded-2xl flex items-center justify-center text-2xl font-bold shadow-inner">
                        <i class="fa-solid fa-users"></i>
                    </div>
                    <div>
                        <p class="text-xs font-semibold text-slate-400 uppercase tracking-wider">Total Siswa Aktif</p>
                        <h3 class="text-4xl font-black text-white mt-1 tracking-tight">366</h3>
                        <span class="inline-flex items-center gap-1 text-[11px] text-emerald-400 font-semibold mt-1 bg-emerald-500/10 px-2 py-0.5 rounded-md">
                            <i class="fa-solid fa-arrow-trend-up"></i> Data Tahun Ini
                        </span>
                    </div>
                </div>
            </div>

            <!-- Card Guru -->
            <div class="glass-card p-6 rounded-3xl shadow-xl relative overflow-hidden group hover:border-emerald-500/50 transition-all duration-300">
                <div class="absolute top-0 right-0 p-6 opacity-10 group-hover:opacity-20 transition-opacity">
                    <i class="fa-solid fa-chalkboard-user text-6xl text-emerald-400"></i>
                </div>
                <div class="flex items-center space-x-4">
                    <div class="w-14 h-14 bg-emerald-500/10 border border-emerald-500/20 text-emerald-400 rounded-2xl flex items-center justify-center text-2xl font-bold shadow-inner">
                        <i class="fa-solid fa-chalkboard"></i>
                    </div>
                    <div>
                        <p class="text-xs font-semibold text-slate-400 uppercase tracking-wider">Dewan Guru & Staff</p>
                        <h3 class="text-4xl font-black text-white mt-1 tracking-tight">10</h3>
                        <span class="inline-flex items-center gap-1 text-[11px] text-emerald-400 font-semibold mt-1 bg-emerald-500/10 px-2 py-0.5 rounded-md">
                            <i class="fa-solid fa-shield-check"></i> Pendidik & Staf Resmi
                        </span>
                    </div>
                </div>
            </div>

            <!-- Card Kepala Sekolah -->
            <div class="glass-card p-6 rounded-3xl shadow-xl relative overflow-hidden group hover:border-purple-500/50 transition-all duration-300">
                <div class="absolute top-0 right-0 p-6 opacity-10 group-hover:opacity-20 transition-opacity">
                    <i class="fa-solid fa-award text-6xl text-purple-400"></i>
                </div>
                <div class="flex items-center space-x-4">
                    <div class="w-14 h-14 bg-purple-500/10 border border-purple-500/20 text-purple-400 rounded-2xl flex items-center justify-center text-2xl font-bold shadow-inner">
                        <i class="fa-solid fa-user-tie"></i>
                    </div>
                    <div>
                        <p class="text-xs font-semibold text-slate-400 uppercase tracking-wider">Kepala Sekolah</p>
                        <h3 class="text-lg font-extrabold text-white mt-1 leading-snug">Sukma, S.Pd</h3>
                        <p class="text-[11px] text-slate-300 mt-0.5 font-mono">NIP. 19680115 199903 1 003</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Detail Informasi & Lokasi -->
        <section class="grid grid-cols-1 lg:grid-cols-3 gap-8">
            <!-- Profil Lokasi -->
            <div class="glass-card p-6 sm:p-8 rounded-3xl shadow-xl space-y-6">
                <div class="flex items-center gap-3 border-b border-slate-700 pb-4">
                    <div class="w-10 h-10 rounded-xl bg-indigo-500/20 text-indigo-400 flex items-center justify-center font-bold">
                        <i class="fa-solid fa-map-location-dot"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white">Alamat & Lokasi</h3>
                </div>
                
                <div class="space-y-4 text-sm text-slate-300">
                    <div class="flex items-start gap-3 bg-slate-900/50 p-3.5 rounded-2xl border border-slate-800">
                        <i class="fa-solid fa-house-chimney text-indigo-400 mt-1"></i>
                        <div>
                            <p class="text-xs text-slate-400 font-medium">Kampung / Dusun</p>
                            <p class="font-semibold text-white mt-0.5">Kp. Kalutuk RT/RW 002/002</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3 bg-slate-900/50 p-3.5 rounded-2xl border border-slate-800">
                        <i class="fa-solid fa-map text-indigo-400 mt-1"></i>
                        <div>
                            <p class="text-xs text-slate-400 font-medium">Desa / Kelurahan</p>
                            <p class="font-semibold text-white mt-0.5">Sukatani</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3 bg-slate-900/50 p-3.5 rounded-2xl border border-slate-800">
                        <i class="fa-solid fa-city text-indigo-400 mt-1"></i>
                        <div>
                            <p class="text-xs text-slate-400 font-medium">Kecamatan & Kabupaten</p>
                            <p class="font-semibold text-white mt-0.5">Kec. Cikande, Serang, Banten</p>
                        </div>
                    </div>
                </div>

                <a href="https://www.google.com/maps/search/?api=1&query=-6.189300,106.311200" target="_blank" class="w-full group relative inline-flex items-center justify-center p-0.5 overflow-hidden rounded-2xl font-medium transition-all">
                    <span class="absolute inset-0 bg-gradient-to-r from-indigo-500 to-blue-600 group-hover:from-indigo-600 group-hover:to-blue-700 transition-all"></span>
                    <span class="relative px-5 py-3 w-full transition-all ease-in duration-75 bg-slate-900 rounded-[14px] group-hover:bg-opacity-0 text-center text-sm font-bold text-white flex items-center justify-center gap-2">
                        <i class="fa-solid fa-compass"></i> Buka Petunjuk Google Maps
                    </span>
                </a>
            </div>

            <!-- Dokumentasi Sekolah (Galeri Foto Asli) -->
            <div class="lg:col-span-2 glass-card p-6 sm:p-8 rounded-3xl shadow-xl space-y-6 flex flex-col justify-between">
                <div>
                    <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 border-b border-slate-700 pb-4">
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 rounded-xl bg-indigo-500/20 text-indigo-400 flex items-center justify-center font-bold">
                                <i class="fa-solid fa-photo-film"></i>
                            </div>
                            <h3 class="text-lg font-bold text-white">Dokumentasi & Gerbang Sekolah</h3>
                        </div>
                        <span class="text-xs text-slate-400 bg-slate-900/60 px-3 py-1 rounded-full border border-slate-700">Lingkungan Utama</span>
                    </div>

                    <div class="mt-6">
                        <!-- Tampilan Foto Asli Sekolah -->
                        <div class="group relative bg-slate-900 rounded-2xl overflow-hidden h-72 border border-slate-700/80 shadow-lg flex items-center justify-center">
                            <img src="IMG_20251028_115038_485.jpg" alt="Gerbang UPT SD Negeri Kalutuk" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                            <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 via-transparent to-transparent flex items-end p-4">
                                <p class="text-xs font-semibold text-white flex items-center gap-2">
                                    <i class="fa-solid fa-location-dot text-indigo-400"></i> Gerbang Depan UPT SD Negeri Kalutuk, Kp. Kalutuk, Ds. Sukatani, Kec. Cikande
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Direktori Dewan Guru & Staf -->
        <section class="glass-card p-6 sm:p-8 rounded-3xl shadow-xl space-y-6">
            <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 border-b border-slate-700 pb-4">
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-xl bg-emerald-500/20 text-emerald-400 flex items-center justify-center font-bold">
                        <i class="fa-solid fa-users-gear"></i>
                    </div>
                    <div>
                        <h3 class="text-lg font-bold text-white">Direktori Dewan Guru & Staf Sekolah</h3>
                        <p class="text-xs text-slate-400">Daftar pendidik dan tenaga kependidikan UPT SD Negeri Kalutuk</p>
                    </div>
                </div>
                <span class="bg-emerald-500/10 border border-emerald-500/20 text-emerald-400 text-xs font-semibold px-3 py-1 rounded-full">
                    Total 10 Personel
                </span>
            </div>

            <!-- Grid Kartu Guru -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 pt-2">
                
                <!-- Guru 1 -->
                <div class="bg-slate-900/80 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between hover:border-indigo-500/40 transition-all">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-[10px] font-bold uppercase tracking-wider bg-blue-500/20 text-blue-400 px-2.5 py-1 rounded-lg border border-blue-500/30">Guru Kelas 1</span>
                            <i class="fa-solid fa-chalkboard-user text-slate-600"></i>
                        </div>
                        <h4 class="font-bold text-white text-base">ETI SUHAETI, S.Pd.</h4>
                        <p class="text-xs text-slate-400 font-mono mt-1">NIP. 19850817 202521 2 085</p>
                    </div>
                </div>

                <!-- Guru 2 -->
                <div class="bg-slate-900/80 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between hover:border-indigo-500/40 transition-all">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-[10px] font-bold uppercase tracking-wider bg-blue-500/20 text-blue-400 px-2.5 py-1 rounded-lg border border-blue-500/30">Guru Kelas 2</span>
                            <i class="fa-solid fa-chalkboard-user text-slate-600"></i>
                        </div>
                        <h4 class="font-bold text-white text-base">MURDAH, S.Pd</h4>
                        <p class="text-xs text-slate-400 font-mono mt-1">NIP. 19710413 200701 2 007</p>
                    </div>
                </div>

                <!-- Guru 3 (Dua Orang) -->
                <div class="bg-slate-900/80 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between hover:border-indigo-500/40 transition-all space-y-4">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-[10px] font-bold uppercase tracking-wider bg-blue-500/20 text-blue-400 px-2.5 py-1 rounded-lg border border-blue-500/30">Guru Kelas 3</span>
                            <i class="fa-solid fa-chalkboard-user text-slate-600"></i>
                        </div>
                        <div class="space-y-3">
                            <div>
                                <h4 class="font-bold text-white text-sm">FAUJIAH, S.Pd.</h4>
                                <p class="text-[11px] text-slate-400 font-mono">NIP. 19700401 200701 2 008</p>
                            </div>
                            <div class="border-t border-slate-800 pt-2">
                                <h4 class="font-bold text-white text-sm">SITI ROHMAH, S.Pd.</h4>
                                <p class="text-[11px] text-slate-400 font-mono">NIP. 19921017 202521 2 144</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Guru 4 -->
                <div class="bg-slate-900/80 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between hover:border-indigo-500/40 transition-all">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-[10px] font-bold uppercase tracking-wider bg-blue-500/20 text-blue-400 px-2.5 py-1 rounded-lg border border-blue-500/30">Guru Kelas 4</span>
                            <i class="fa-solid fa-chalkboard-user text-slate-600"></i>
                        </div>
                        <h4 class="font-bold text-white text-base">ATIKAH, S.Pd</h4>
                        <p class="text-xs text-slate-400 font-mono mt-1">NIP. 19701105 200701 2 013</p>
                    </div>
                </div>

                <!-- Guru 5 -->
                <div class="bg-slate-900/80 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between hover:border-indigo-500/40 transition-all">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-[10px] font-bold uppercase tracking-wider bg-blue-500/20 text-blue-400 px-2.5 py-1 rounded-lg border border-blue-500/30">Guru Kelas 5</span>
                            <i class="fa-solid fa-chalkboard-user text-slate-600"></i>
                        </div>
                        <h4 class="font-bold text-white text-base">MILA YULIANAH, S.Pd</h4>
                        <p class="text-xs text-slate-400 font-mono mt-1">NIP. 19870104 202521 2 094</p>
                    </div>
                </div>

                <!-- Guru 6 -->
                <div class="bg-slate-900/80 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between hover:border-indigo-500/40 transition-all">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-[10px] font-bold uppercase tracking-wider bg-blue-500/20 text-blue-400 px-2.5 py-1 rounded-lg border border-blue-500/30">Guru Kelas 6</span>
                            <i class="fa-solid fa-chalkboard-user text-slate-600"></i>
                        </div>
                        <h4 class="font-bold text-white text-base">UCU ANDARIAH, S.Pd</h4>
                        <p class="text-xs text-slate-400 font-mono mt-1">NIP. 19940811 202521 2 134</p>
                    </div>
                </div>

                <!-- Guru PJOK -->
                <div class="bg-slate-900/80 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between hover:border-indigo-500/40 transition-all">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-[10px] font-bold uppercase tracking-wider bg-purple-500/20 text-purple-400 px-2.5 py-1 rounded-lg border border-purple-500/30">Guru PJOK</span>
                            <i class="fa-solid fa-person-running text-slate-600"></i>
                        </div>
                        <h4 class="font-bold text-white text-base">DAVA DEFITRA, S.Pd.</h4>
                        <p class="text-xs text-slate-400 font-mono mt-1">Pendidikan Jasmani & Kesehatan</p>
                    </div>
                </div>

                <!-- TAS -->
                <div class="bg-slate-900/80 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between hover:border-indigo-500/40 transition-all">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-[10px] font-bold uppercase tracking-wider bg-amber-500/20 text-amber-400 px-2.5 py-1 rounded-lg border border-amber-500/30">Tenaga Administrasi</span>
                            <i class="fa-solid fa-id-badge text-slate-600"></i>
                        </div>
                        <h4 class="font-bold text-white text-base">MUHAMMAD HANIEF K.</h4>
                        <p class="text-xs text-slate-400 font-mono mt-1">S.Kom (TAS)</p>
                    </div>
                </div>

                <!-- Tenaga Kebersihan -->
                <div class="bg-slate-900/80 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between hover:border-indigo-500/40 transition-all">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-[10px] font-bold uppercase tracking-wider bg-rose-500/20 text-rose-400 px-2.5 py-1 rounded-lg border border-rose-500/30">Kebersihan</span>
                            <i class="fa-solid fa-broom text-slate-600"></i>
                        </div>
                        <h4 class="font-bold text-white text-base">Nuraeniah</h4>
                        <p class="text-xs text-slate-400 font-mono mt-1">Tenaga Kebersihan Sekolah</p>
                    </div>
                </div>

            </div>
        </section>

        <!-- Kegiatan Ekstrakurikuler & Dokumentasi Pramuka -->
        <section class="glass-card p-6 sm:p-8 rounded-3xl shadow-xl space-y-6">
            <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 border-b border-slate-700 pb-4">
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-xl bg-amber-500/20 text-amber-400 flex items-center justify-center font-bold">
                        <i class="fa-solid fa-signs-post"></i>
                    </div>
                    <div>
                        <h3 class="text-lg font-bold text-white">Kegiatan Ekstrakurikuler Pramuka</h3>
                        <p class="text-xs text-slate-400">Pengembangan bakat, karakter, dan kedisiplinan siswa siswi</p>
                    </div>
                </div>
                <span class="bg-amber-500/10 border border-amber-500/20 text-amber-400 text-xs font-semibold px-3 py-1 rounded-full">
                    Ekstrakurikuler Unggulan
                </span>
            </div>

            <!-- Konten Pramuka & Galeri Fotonya -->
            <div class="space-y-6">
                <!-- Deskripsi -->
                <div class="bg-gradient-to-br from-amber-950/30 via-slate-900 to-slate-900 border border-amber-500/30 p-6 rounded-3xl space-y-4">
                    <div class="inline-flex items-center gap-2 bg-amber-500/20 text-amber-300 text-xs font-bold px-3 py-1 rounded-full border border-amber-500/30">
                        <i class="fa-solid fa-star text-[10px]"></i> Wajib & Aktif
                    </div>
                    <h4 class="text-2xl font-black text-white tracking-tight">Gerakan Pramuka UPT SD Negeri Kalutuk</h4>
                    <p class="text-sm text-slate-300 leading-relaxed">
                        Pramuka merupakan kegiatan ekstrakurikuler unggulan di UPT SD Negeri Kalutuk yang bertujuan membentuk kepribadian yang beriman, bertakwa, berakhlak mulia, berjiwa patriotik, taat hukum, dan disiplin melalui latihan kepramukaan berkala di halaman sekolah.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-1">
                        <span class="bg-slate-800/80 border border-slate-700 text-slate-300 text-xs px-3 py-1.5 rounded-xl font-medium"><i class="fa-solid fa-check text-amber-400 mr-1.5"></i> Siaga & Penggalang</span>
                        <span class="bg-slate-800/80 border border-slate-700 text-slate-300 text-xs px-3 py-1.5 rounded-xl font-medium"><i class="fa-solid fa-check text-amber-400 mr-1.5"></i> Apel & Baris-Berbaris</span>
                        <span class="bg-slate-800/80 border border-slate-700 text-slate-300 text-xs px-3 py-1.5 rounded-xl font-medium"><i class="fa-solid fa-check text-amber-400 mr-1.5"></i> Pembentukan Karakter</span>
                    </div>
                </div>

                <!-- Galeri Foto Dokumentasi Pramuka (2 Foto Asli) -->
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- Foto 1 -->
                    <div class="group relative bg-slate-900 rounded-3xl overflow-hidden h-72 border border-slate-700/80 shadow-xl flex items-center justify-center">
                        <img src="EKSTRAKURIKULER PRAMUKA. 2.jpeg" alt="Dokumentasi Pramuka 2" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 via-transparent to-transparent flex items-end p-4">
                            <p class="text-xs font-semibold text-white flex items-center gap-2">
                                <i class="fa-solid fa-camera text-amber-400"></i> Kegiatan Apel & Latihan Pramuka Siswa-Siswi
                            </p>
                        </div>
                    </div>
                    <!-- Foto 2 -->
                    <div class="group relative bg-slate-900 rounded-3xl overflow-hidden h-72 border border-slate-700/80 shadow-xl flex items-center justify-center">
                        <img src="EKSTRAKURIKULER PRAMUKA. 3.jpeg" alt="Dokumentasi Pramuka 3" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 via-transparent to-transparent flex items-end p-4">
                            <p class="text-xs font-semibold text-white flex items-center gap-2">
                                <i class="fa-solid fa-camera text-amber-400"></i> Arahan Pembina Pramuka di Lapangan Sekolah
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-slate-950 border-t border-slate-800 mt-16 py-8 text-center text-xs text-slate-500">
        <div class="max-w-7xl mx-auto px-4 space-y-2">
            <p class="font-medium text-slate-400">&copy; 2026 UPT SD Negeri Kalutuk. All Rights Reserved.</p>
            <p>Kp. Kalutuk RT/RW 002/002, Desa Sukatani, Kecamatan Cikande, Kabupaten Serang, Banten.</p>
        </div>
    </footer>

</body>
</html>
