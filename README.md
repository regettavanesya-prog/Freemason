
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jejak Freemason di Malang - Pusat Dokumentasi & Arsip Digital</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Playfair Display (Serif Klasik) & Inter (Sans-Serif) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;700;900&family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        archive: {
                            bg: '#120d0a',        /* Cokelat Hitam Sangat Tua */
                            dark: '#1c1510',      /* Cokelat Kayu Glap */
                            card: '#281e17',      /* Cokelat Panel */
                            border: '#423327',    /* Border Cokelat Tembaga */
                            accent: '#c89d54',    /* Emas Muted */
                            accentHover: '#e5b869',/* Emas Terang */
                            paper: '#f4ebd0',     /* Krem Kertas Tua */
                            paperDark: '#e2d3b2', /* Krem Agak Gelap */
                            text: '#2c221a',      /* Teks Cokelat Tua */
                            muted: '#8c7663'      /* Teks Muted */
                        }
                    },
                    fontFamily: {
                        cinzel: ['Cinzel', 'serif'],
                        serif: ['Playfair Display', 'serif'],
                        sans: ['Plus Jakarta Sans', 'sans-serif']
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom Scrollbar Motif Klasik */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #120d0a;
        }
        ::-webkit-scrollbar-thumb {
            background: #423327;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #c89d54;
        }
        .paper-texture {
            background-color: #f4ebd0;
            background-image: radial-gradient(#c89d54 0.5px, transparent 0.5px), radial-gradient(#c89d54 0.5px, #f4ebd0 0.5px);
            background-size: 20px 20px;
            background-position: 0 0, 10px 10px;
            background-opacity: 0.05;
        }
        .gold-border-gradient {
            border-image: linear-gradient(to bottom, #c89d54, #423327, #c89d54) 1;
        }
        .vintage-shadow {
            box-shadow: 0 10px 30px -10px rgba(0, 0, 0, 0.7);
        }
    </style>
</head>
<body class="bg-archive-bg text-archive-paper font-sans antialiased selection:bg-archive-accent selection:text-archive-dark min-h-screen flex flex-col">

    <!-- TOP HEADER / ANNOUNCEMENT BANNER -->
    <div class="bg-archive-dark border-b border-archive-border py-2 px-4 text-xs text-center text-archive-paper/80 font-serif">
        <i class="fa-solid fa-landmark text-archive-accent mr-2"></i>
        Pusat Dokumentasi Digital Sejarah Kolonial & Kebudayaan Kota Malang — Portofolio Arsip Publik
    </div>

    <!-- NAVIGATION BAR -->
    <nav class="sticky top-0 z-40 bg-archive-bg/95 backdrop-blur-md border-b border-archive-border/80 shadow-2xl">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Logo & Brand -->
                <a href="#home" class="flex items-center gap-3 group">
                    <div class="w-10 h-10 rounded-full border border-archive-accent/60 bg-archive-dark flex items-center justify-center text-archive-accent group-hover:border-archive-accent transition-colors shadow-inner">
                        <i class="fa-solid fa-compass-drafting text-lg"></i>
                    </div>
                    <div>
                        <span class="font-cinzel text-lg sm:text-xl font-bold tracking-wider text-archive-accent block leading-tight">JEJAK FREEMASON</span>
                        <span class="text-[10px] tracking-widest text-archive-paper/60 uppercase block font-sans">Kota Malang • Jawa Timur</span>
                    </div>
                </a>

                <!-- Desktop Nav Links -->
                <div class="hidden lg:flex items-center space-x-1 xl:space-x-2 text-sm font-medium">
                    <a href="#home" class="px-3 py-2 rounded-md hover:text-archive-accent transition-colors border-b-2 border-transparent hover:border-archive-accent">Beranda</a>
                    <a href="#galeri" class="px-3 py-2 rounded-md hover:text-archive-accent transition-colors border-b-2 border-transparent hover:border-archive-accent">Galeri Foto</a>
                    <a href="#arsip" class="px-3 py-2 rounded-md hover:text-archive-accent transition-colors border-b-2 border-transparent hover:border-archive-accent">Arsip Digital</a>
                    <a href="#literatur" class="px-3 py-2 rounded-md hover:text-archive-accent transition-colors border-b-2 border-transparent hover:border-archive-accent">Literatur</a>
                    <a href="#timeline" class="px-3 py-2 rounded-md hover:text-archive-accent transition-colors border-b-2 border-transparent hover:border-archive-accent">Timeline</a>
                    <a href="#peta" class="px-3 py-2 rounded-md hover:text-archive-accent transition-colors border-b-2 border-transparent hover:border-archive-accent">Peta Sejarah</a>
                    <a href="#referensi" class="px-3 py-2 rounded-md hover:text-archive-accent transition-colors border-b-2 border-transparent hover:border-archive-accent">Referensi</a>
                </div>

                <!-- Admin Upload Button & Mobile Menu Toggle -->
                <div class="flex items-center gap-3">
                    <button onclick="openUploadModal()" class="hidden sm:inline-flex items-center gap-2 px-3.5 py-1.5 rounded-md bg-archive-accent/10 border border-archive-accent/50 text-archive-accent text-xs font-semibold hover:bg-archive-accent hover:text-archive-dark transition-all duration-300">
                        <i class="fa-solid fa-upload"></i>
                        <span>Unggah Arsip</span>
                    </button>

                    <button id="mobile-menu-btn" class="lg:hidden p-2 rounded-md text-archive-paper hover:text-archive-accent focus:outline-none">
                        <i class="fa-solid fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Navigation Menu -->
        <div id="mobile-menu" class="hidden lg:hidden border-t border-archive-border bg-archive-dark px-4 pt-2 pb-6 space-y-2">
            <a href="#home" class="mobile-link block px-3 py-2 rounded-md text-base hover:bg-archive-card hover:text-archive-accent">Beranda</a>
            <a href="#galeri" class="mobile-link block px-3 py-2 rounded-md text-base hover:bg-archive-card hover:text-archive-accent">Galeri Foto</a>
            <a href="#arsip" class="mobile-link block px-3 py-2 rounded-md text-base hover:bg-archive-card hover:text-archive-accent">Arsip Digital</a>
            <a href="#literatur" class="mobile-link block px-3 py-2 rounded-md text-base hover:bg-archive-card hover:text-archive-accent">Buku & Literatur</a>
            <a href="#timeline" class="mobile-link block px-3 py-2 rounded-md text-base hover:bg-archive-card hover:text-archive-accent">Timeline Sejarah</a>
            <a href="#peta" class="mobile-link block px-3 py-2 rounded-md text-base hover:bg-archive-card hover:text-archive-accent">Peta Sejarah Interaktif</a>
            <a href="#referensi" class="mobile-link block px-3 py-2 rounded-md text-base hover:bg-archive-card hover:text-archive-accent">Daftar Referensi</a>
            <button onclick="openUploadModal()" class="w-full text-left mt-3 px-3 py-2 rounded-md bg-archive-accent text-archive-dark font-bold flex items-center justify-center gap-2">
                <i class="fa-solid fa-upload"></i> Unggah Kontribusi Arsip
            </button>
        </div>
    </nav>

    <!-- HERO SECTION / SEKSI UTAMA -->
    <section id="home" class="relative py-20 lg:py-28 overflow-hidden border-b border-archive-border bg-gradient-to-b from-archive-bg via-archive-dark to-archive-bg">
        <!-- Overlay Vintage Grid Background -->
        <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#c89d54_1px,transparent_1px)] [background-size:16px_16px] pointer-events-none"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid lg:grid-cols-12 gap-12 items-center">
                
                <!-- Hero Left Column -->
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full border border-archive-accent/40 bg-archive-card/60 text-archive-accent text-xs tracking-widest uppercase font-semibold">
                        <i class="fa-solid fa-scroll"></i> Portal Dokumentasi & Riset Sejarah
                    </div>
                    
                    <h1 class="font-cinzel text-3xl sm:text-5xl lg:text-6xl font-extrabold text-archive-paper leading-tight tracking-wide">
                        Jejak <span class="text-archive-accent underline decoration-archive-accent/40 decoration-wavy">Freemason</span> di Malang
                    </h1>

                    <p class="font-serif text-lg sm:text-xl text-archive-paperDark italic leading-relaxed">
                        "Menelusuri Sejarah, Mengungkap Arsip, dan Mendokumentasikan Warisan Masa Lalu."
                    </p>

                    <p class="text-archive-paper/80 text-sm sm:text-base leading-relaxed max-w-2xl mx-auto lg:mx-0 font-sans">
                        Selamat datang di pusat studi dan preservasi digital sejarah keberadaan Loji Freemason (<em>Masonic Lodge / Vrijmetselarij</em>) di Malang pada era Hindia Belanda. Portal ini dirancang untuk menghimpun dokumen, klipping surat kabar, literatur, dan situs cagar budaya secara obyektif berdasarkan bukti historis yang dapat diverifikasi.
                    </p>

                    <!-- Quick Stats Badges -->
                    <div class="grid grid-cols-3 gap-4 pt-4 border-t border-archive-border/60 max-w-md mx-auto lg:mx-0">
                        <div class="text-center lg:text-left">
                            <span class="block font-cinzel text-2xl font-bold text-archive-accent">1901+</span>
                            <span class="text-xs text-archive-paper/60 uppercase">Masa Keberadaan</span>
                        </div>
                        <div class="text-center lg:text-left border-x border-archive-border/60 px-2">
                            <span class="block font-cinzel text-2xl font-bold text-archive-accent">12+</span>
                            <span class="text-xs text-archive-paper/60 uppercase">Dokumen Kunci</span>
                        </div>
                        <div class="text-center lg:text-left">
                            <span class="block font-cinzel text-2xl font-bold text-archive-accent">100%</span>
                            <span class="text-xs text-archive-paper/60 uppercase">Akademis & Terbuka</span>
                        </div>
                    </div>

                    <div class="pt-2 flex flex-wrap justify-center lg:justify-start gap-4">
                        <a href="#arsip" class="px-6 py-3 rounded-lg bg-archive-accent text-archive-dark font-bold text-sm tracking-wider uppercase hover:bg-archive-accentHover transition-all shadow-lg flex items-center gap-2">
                            <i class="fa-solid fa-folder-open"></i> Jelajahi Arsip Digital
                        </a>
                        <a href="#peta" class="px-6 py-3 rounded-lg border border-archive-accent/50 text-archive-paper hover:bg-archive-card font-medium text-sm tracking-wider uppercase transition-all flex items-center gap-2">
                            <i class="fa-solid fa-map-location-dot text-archive-accent"></i> Lihat Peta Lokasi
                        </a>
                    </div>
                </div>

                <!-- Hero Right Column: Vintage Visual Card Showcase -->
                <div class="lg:col-span-5">
                    <div class="relative mx-auto max-w-md lg:max-w-none">
                        <div class="absolute -inset-1 rounded-2xl bg-gradient-to-r from-archive-accent/30 to-archive-border opacity-75 blur-md"></div>
                        <div class="relative bg-archive-card border border-archive-border rounded-2xl p-4 sm:p-6 space-y-4 shadow-2xl">
                            <div class="relative rounded-lg overflow-hidden border border-archive-border/80 group">
                                <img src="https://i1.wp.com/risetcdn.jatimtimes.com/images/2020/12/27/Potret-kawasan-Balai-Kota-Malang-zaman-dahulu.-Foto-Screen-Capture-video-Bimo-K.A.7f55fd882cbe9470.jpg?quality=80&strip=all">
                                <div class="absolute inset-0 bg-gradient-to-t from-archive-dark via-transparent to-transparent opacity-80"></div>
                                <div class="absolute bottom-3 left-3 right-3 text-xs">
                                    <span class="bg-archive-accent/90 text-archive-dark font-bold px-2 py-0.5 rounded text-[10px]">ARSIP FOTO NATIVE</span>
                                    <p class="text-archive-paper font-serif italic mt-1">Gedung dan suasana Kota Malang abad ke-20</p>
                                </div>
                            </div>
                            <div class="p-3 bg-archive-dark/80 rounded-lg border border-archive-border/50 text-xs text-archive-paper/80 space-y-1">
                                <p class="font-semibold text-archive-accent"><i class="fa-solid fa-circle-info mr-1"></i> Catatan Editor Museum:</p>
                                <p class="italic">"Penelitian mengenai Loji Freemason Malang ('Malangsche Loge') senantiasa berpedoman pada sumber arsip resmi, warta pers sejarah Hindia Belanda, dan peta kolonial."</p>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- SEARCH AND FILTER GLOBAL BAR -->
    <section class="bg-archive-dark border-b border-archive-border py-6 px-4">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-4">
            <div class="w-full md:w-1/2 relative">
                <i class="fa-solid fa-magnifying-glass absolute left-4 top-1/2 -translate-y-1/2 text-archive-muted"></i>
                <input type="text" id="global-search" oninput="filterGlobalCollections()" placeholder="Cari dokumen, foto, judul koran, atau nama tokoh..." class="w-full bg-archive-bg border border-archive-border rounded-lg pl-11 pr-4 py-2.5 text-sm text-archive-paper placeholder-archive-muted focus:outline-none focus:border-archive-accent transition-colors">
            </div>
            
            <div class="flex items-center gap-3 w-full md:w-auto overflow-x-auto pb-2 md:pb-0">
                <span class="text-xs text-archive-muted uppercase font-bold whitespace-nowrap"><i class="fa-solid fa-filter mr-1"></i> Filter Era:</span>
                <button onclick="setYearFilter('all')" class="filter-btn active text-xs px-3 py-1.5 rounded-full border border-archive-accent bg-archive-accent text-archive-dark font-semibold whitespace-nowrap">Semua Era</button>
                <button onclick="setYearFilter('1900')" class="filter-btn text-xs px-3 py-1.5 rounded-full border border-archive-border bg-archive-card text-archive-paper hover:border-archive-accent transition-colors whitespace-nowrap">1900 - 1920</button>
                <button onclick="setYearFilter('1920')" class="filter-btn text-xs px-3 py-1.5 rounded-full border border-archive-border bg-archive-card text-archive-paper hover:border-archive-accent transition-colors whitespace-nowrap">1921 - 1940</button>
                <button onclick="setYearFilter('1940')" class="filter-btn text-xs px-3 py-1.5 rounded-full border border-archive-border bg-archive-card text-archive-paper hover:border-archive-accent transition-colors whitespace-nowrap">1941 - Pasca Kemerdekaan</button>
            </div>
        </div>
    </section>

    <!-- SECTION 1: GALERI FOTO -->
    <section id="galeri" class="py-16 border-b border-archive-border bg-archive-bg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-10 border-b border-archive-border/60 pb-4">
                <div>
                    <div class="text-archive-accent text-xs font-bold tracking-widest uppercase mb-1">Dokumentasi Visual</div>
                    <h2 class="font-cinzel text-2xl sm:text-3xl font-bold text-archive-paper">Galeri Foto & Bangunan Sejarah</h2>
                </div>
                <p class="text-xs text-archive-paper/60 mt-2 md:mt-0 max-w-md">Koleksi foto visual lanskap Malang tempo dulu, gedung-gedung bersejarah kolonial, serta potret kegiatan masyarakat era 1900-1940-an.</p>
            </div>

            <!-- Grid Foto -->
            <div id="gallery-grid" class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Injected via JavaScript for Interactive Search/Filter -->
            </div>
        </div>
    </section>

    <!-- SECTION 2: ARSIP DIGITAL (DOKUMEN & KORAN KUNCI) -->
    <section id="arsip" class="py-16 border-b border-archive-border bg-archive-dark">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-10 border-b border-archive-border/60 pb-4">
                <div>
                    <div class="text-archive-accent text-xs font-bold tracking-widest uppercase mb-1">Preservasi Naskah & Pers</div>
                    <h2 class="font-cinzel text-2xl sm:text-3xl font-bold text-archive-paper">Ruang Arsip Digital & Surat Kabar</h2>
                </div>
                <p class="text-xs text-archive-paper/60 mt-2 md:mt-0 max-w-md">Menyimpan kliping koran Belanda, buku direktori, surat administrasi, dan peta tempo dulu beserta status konfirmasi validasi riset.</p>
            </div>

            <!-- Warning Callout Box for Verification Status -->
            <div class="mb-8 p-4 rounded-lg bg-archive-card border-l-4 border-archive-accent text-xs text-archive-paper/90 space-y-1 leading-relaxed">
                <span class="font-bold text-archive-accent block uppercase"><i class="fa-solid fa-triangle-exclamation mr-1"></i> Catatan Transparansi Riset:</span>
                Sebagian arsip bertanda <span class="bg-amber-900/50 text-amber-300 px-1.5 py-0.5 rounded font-mono text-[10px]">Petunjuk Pencarian</span> merupakan rujukan bibliografi sejarah yang teks/entri fisiknya masih dalam tahap proses penelusuran lebih lanjut di perpustakaan/arsip daerah.
            </div>

            <!-- Grid Arsip Digital -->
            <div id="archive-grid" class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Injected via JavaScript -->
            </div>
        </div>
    </section>

    <!-- SECTION 3: KOLEKSI BUKU & LITERATUR PERPUSTAKAAN -->
    <section id="literatur" class="py-16 border-b border-archive-border bg-archive-bg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-10 border-b border-archive-border/60 pb-4">
                <div>
                    <div class="text-archive-accent text-xs font-bold tracking-widest uppercase mb-1">Perpustakaan Digital</div>
                    <h2 class="font-cinzel text-2xl sm:text-3xl font-bold text-archive-paper">Koleksi Buku & Literatur Akademis</h2>
                </div>
                <p class="text-xs text-archive-paper/60 mt-2 md:mt-0 max-w-md">Buku referensi, studi historis organisasi kemasyarakatan masa kolonial, serta literatur sejarah perkembangan Kota Malang.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Book Card 1: Malang Tempo Doeloe (UKWK Link Included) -->
                <div class="bg-archive-card border border-archive-border rounded-xl overflow-hidden hover:border-archive-accent transition-all duration-300 flex flex-col justify-between p-5">
                    <div class="space-y-4">
                        <div class="flex gap-4">
                            <div class="w-20 h-28 bg-archive-dark border border-archive-border rounded flex-shrink-0 flex items-center justify-center text-archive-accent">
                                <i class="fa-solid fa-book-bookmark text-3xl"></i>
                            </div>
                            <div>
                                <span class="text-[10px] bg-archive-accent/20 text-archive-accent font-semibold px-2 py-0.5 rounded">Buku Sejarah Lokal</span>
                                <h3 class="font-serif font-bold text-archive-paper text-base mt-1">Malang Tempo Doeloe</h3>
                                <p class="text-xs text-archive-paper/60">Penulis: Dukut Imam Widodo</p>
                                <p class="text-xs text-archive-muted mt-1">Penerbit: Bayumedia (2006)</p>
                            </div>
                        </div>
                        <p class="text-xs text-archive-paper/80 leading-relaxed">
                            Karya komprehensif mengenai tata kota, kehidupan sosial, gedung-gedung bersejarah, serta dinamika komunitas masyarakat Malang pada era Hindia Belanda.
                        </p>
                    </div>
                    <div class="mt-5 pt-4 border-t border-archive-border/60 flex items-center justify-between">
                        <span class="text-[11px] text-archive-muted"><i class="fa-solid fa-building-columns mr-1"></i> Perpustakaan UKWK</span>
                        <a href="https://digilib.ukwk.ac.id/index.php?p=show_detail&id=3669" target="_blank" rel="noopener noreferrer" class="text-xs text-archive-accent hover:underline font-bold flex items-center gap-1">
                            Katalog UKWK <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Book Card 2: Karmelindo Entry -->
                <div class="bg-archive-card border border-archive-border rounded-xl overflow-hidden hover:border-archive-accent transition-all duration-300 flex flex-col justify-between p-5">
                    <div class="space-y-4">
                        <div class="flex gap-4">
                            <div class="w-20 h-28 bg-archive-dark border border-archive-border rounded flex-shrink-0 flex items-center justify-center text-archive-accent">
                                <i class="fa-solid fa-book-atlas text-3xl"></i>
                            </div>
                            <div>
                                <span class="text-[10px] bg-archive-accent/20 text-archive-accent font-semibold px-2 py-0.5 rounded">Katalog Riset Perpustakaan</span>
                                <h3 class="font-serif font-bold text-archive-paper text-base mt-1">Koleksi Studi Sejarah Malang & Jawa Timur</h3>
                                <p class="text-xs text-archive-paper/60">Pengarang / Arsiparis Terkait</p>
                                <p class="text-xs text-archive-muted mt-1">Perpustakaan Karmelindo</p>
                            </div>
                        </div>
                        <p class="text-xs text-archive-paper/80 leading-relaxed">
                            Catatan entri bibliografi perpustakaan mengenai rekaman sejarah lokal, perkembangan arsitektur, dan pertumbuhan organisasi sosial di Malang.
                        </p>
                    </div>
                    <div class="mt-5 pt-4 border-t border-archive-border/60 flex items-center justify-between">
                        <span class="text-[11px] text-archive-muted"><i class="fa-solid fa-bookmark mr-1"></i> Karmelindo Org</span>
                        <a href="https://www.perpustakaankarmelindo.org/index.php?id=207110&p=show_detail" target="_blank" rel="noopener noreferrer" class="text-xs text-archive-accent hover:underline font-bold flex items-center gap-1">
                            Buka Detail <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Book Card 3: Tarekat Mason Bebas di Indonesia -->
                <div class="bg-archive-card border border-archive-border rounded-xl overflow-hidden hover:border-archive-accent transition-all duration-300 flex flex-col justify-between p-5">
                    <div class="space-y-4">
                        <div class="flex gap-4">
                            <div class="w-20 h-28 bg-archive-dark border border-archive-border rounded flex-shrink-0 flex items-center justify-center text-archive-accent">
                                <i class="fa-solid fa-scroll text-3xl"></i>
                            </div>
                            <div>
                                <span class="text-[10px] bg-archive-accent/20 text-archive-accent font-semibold px-2 py-0.5 rounded">Jurnal Akademis</span>
                                <h3 class="font-serif font-bold text-archive-paper text-base mt-1">Vrijmetselarij in Nederlandsch-Indië</h3>
                                <p class="text-xs text-archive-paper/60">Penulis: Dr. Th. Stevens</p>
                                <p class="text-xs text-archive-muted mt-1">Studi Historiografi (1764–1962)</p>
                            </div>
                        </div>
                        <p class="text-xs text-archive-paper/80 leading-relaxed">
                            Buku referensi standar mengenai sejarah Freemasonry di Hindia Belanda, termasuk pendirian loge-loge di kota sekunder seperti Malang, Pasuruan, dan Surabaya.
                        </p>
                    </div>
                    <div class="mt-5 pt-4 border-t border-archive-border/60 flex items-center justify-between">
                        <span class="text-[11px] text-archive-muted"><i class="fa-solid fa-graduation-cap mr-1"></i> Publikasi Ilmiah</span>
                        <span class="text-xs text-archive-paper/50 italic">Referensi Fisik Perpustakaan</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION 4: TIMELINE SEJARAH INTERAKTIF -->
    <section id="timeline" class="py-16 border-b border-archive-border bg-archive-dark">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-12">
                <div class="text-archive-accent text-xs font-bold tracking-widest uppercase mb-1">Garis Waktu Kronologis</div>
                <h2 class="font-cinzel text-2xl sm:text-3xl font-bold text-archive-paper">Perkembangan Sejarah & Peristiwa</h2>
                <p class="text-xs text-archive-paper/60 mt-2">Kronologi keterkaitan Freemason dengan dinamika perkotaan Malang berdasarkan pencatatan arsip kolonial.</p>
            </div>

            <div class="relative border-l-2 border-archive-accent/40 max-w-3xl mx-auto space-y-10 pl-6 sm:pl-8">
                
                <!-- Item 1 -->
                <div class="relative group">
                    <div class="absolute -left-[31px] sm:-left-[39px] top-1 w-5 h-5 rounded-full bg-archive-accent border-4 border-archive-dark"></div>
                    <div class="bg-archive-card border border-archive-border rounded-xl p-5 hover:border-archive-accent transition-colors">
                        <span class="text-xs font-bold font-mono text-archive-accent bg-archive-dark px-2.5 py-1 rounded border border-archive-accent/30 inline-block mb-2">Tahun 1901–1902</span>
                        <h3 class="font-serif font-bold text-archive-paper text-lg">Inisiasi Komunitas & Pembentukan Loji Malang</h3>
                        <p class="text-xs text-archive-paper/80 mt-2 leading-relaxed">
                            Mulai berdirinya lingkaran warga sipil dan pejabat Hindia Belanda di Malang yang terafiliasi dengan Loge induk di Surabaya (Loge De Vriendschap). Perkumpulan awal diadakan di kediaman perorangan sebelum menyewa tempat khusus.
                        </p>
                    </div>
                </div>

                <!-- Item 2 -->
                <div class="relative group">
                    <div class="absolute -left-[31px] sm:-left-[39px] top-1 w-5 h-5 rounded-full bg-archive-accent border-4 border-archive-dark"></div>
                    <div class="bg-archive-card border border-archive-border rounded-xl p-5 hover:border-archive-accent transition-colors">
                        <span class="text-xs font-bold font-mono text-archive-accent bg-archive-dark px-2.5 py-1 rounded border border-archive-accent/30 inline-block mb-2">15 Februari 1927</span>
                        <h3 class="font-serif font-bold text-archive-paper text-lg">Peringatan 25 Tahun (Yubileum Loge Malang)</h3>
                        <p class="text-xs text-archive-paper/80 mt-2 leading-relaxed">
                            Berdasarkan laporan surat kabar <em>De Locomotief</em> (15 Feb 1927, Halaman 3), dicatat peringatan seperempat abad keberadaan organisasi loge Freemason di Malang. Petunjuk ini menjadi salah satu dasar penghitungan usia loji lokal.
                        </p>
                    </div>
                </div>

                <!-- Item 3 -->
                <div class="relative group">
                    <div class="absolute -left-[31px] sm:-left-[39px] top-1 w-5 h-5 rounded-full bg-archive-accent border-4 border-archive-dark"></div>
                    <div class="bg-archive-card border border-archive-border rounded-xl p-5 hover:border-archive-accent transition-colors">
                        <span class="text-xs font-bold font-mono text-archive-accent bg-archive-dark px-2.5 py-1 rounded border border-archive-accent/30 inline-block mb-2">Tahun 1930 - 1941</span>
                        <h3 class="font-serif font-bold text-archive-paper text-lg">Direktori Alamat & Kegiatan Sosial Organisasi</h3>
                        <p class="text-xs text-archive-paper/80 mt-2 leading-relaxed">
                            Pencatatan alamat organisasi dalam buku panduan direktori Hindia Belanda seperti <em>Kleian’s Adresboek van Geheel Nederlandsch-Indië</em>. Kegiatan loji pada masa ini banyak berfokus pada perpustakaan internal, pengumpulan dana amal (Eersterang), dan diskusi kebudayaan.
                        </p>
                    </div>
                </div>

                <!-- Item 4 -->
                <div class="relative group">
                    <div class="absolute -left-[31px] sm:-left-[39px] top-1 w-5 h-5 rounded-full bg-archive-accent border-4 border-archive-dark"></div>
                    <div class="bg-archive-card border border-archive-border rounded-xl p-5 hover:border-archive-accent transition-colors">
                        <span class="text-xs font-bold font-mono text-archive-accent bg-archive-dark px-2.5 py-1 rounded border border-archive-accent/30 inline-block mb-2">Tahun 1942–1962</span>
                        <h3 class="font-serif font-bold text-archive-paper text-lg">Masa Pendudukan Jepang hingga Pembekuan Resmi</h3>
                        <p class="text-xs text-archive-paper/80 mt-2 leading-relaxed">
                            Pada era Perang Dunia II dan pendudukan Jepang, seluruh aktivitas Freemason dilarang keras. Gedung-gedung loji disita atau dialihfungsikan. Pasca kemerdekaan RI, melalui Keputusan Presiden No. 264 Tahun 1962, organisasi ini resmi dibekukan di seluruh wilayah Indonesia.
                        </p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- SECTION 5: PETA SEJARAH INTERAKTIF MALANG -->
    <section id="peta" class="py-16 border-b border-archive-border bg-archive-bg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-8 border-b border-archive-border/60 pb-4">
                <div>
                    <div class="text-archive-accent text-xs font-bold tracking-widest uppercase mb-1">Geografi Sejarah</div>
                    <h2 class="font-cinzel text-2xl sm:text-3xl font-bold text-archive-paper">Peta Sejarah Interaktif Kota Malang</h2>
                </div>
                <p class="text-xs text-archive-paper/60 mt-2 md:mt-0 max-w-md">Klik titik penanda lokasi di bawah untuk melihat foto sejarah, keterangan bangunan, dan konteks kolonial.</p>
            </div>

            <!-- Simulated Interactive Map Viewer Container -->
            <div class="grid lg:grid-cols-12 gap-6 bg-archive-dark border border-archive-border rounded-2xl p-4 sm:p-6 shadow-2xl">
                
                <!-- Visual Map Interactive Display -->
                <div class="lg:col-span-8 bg-archive-bg rounded-xl border border-archive-border relative overflow-hidden min-h-[350px] sm:min-h-[450px] flex items-center justify-center">
                    <!-- Map Background Vintage Image Overlay -->
                    <img src="https://images.unsplash.com/photo-1524661135-423995f22d0b?auto=format&fit=crop&w=1200&q=80https://perpustakaankarmelindo.org/lib/minigalnano/createthumb.php?filename=images/docs/11.755..jpg&width=200" alt="Sketsa Peta Malang Tempo Dulu" class="absolute inset-0 w-full h-full object-cover opacity-20 filter sepia">
                    
                    <div class="absolute top-3 left-3 bg-archive-dark/90 px-3 py-1.5 rounded border border-archive-border text-xs text-archive-paper">
                        <i class="fa-solid fa-map text-archive-accent mr-1"></i> Peta Wilayah Malang Kolonial (Simulasi Visual)
                    </div>

                    <!-- Interactive Pin 1 -->
                    <button onclick="selectMapLocation(0)" class="map-pin absolute top-[35%] left-[45%] transform -translate-x-1/2 -translate-y-1/2 group focus:outline-none">
                        <span class="relative flex h-6 w-6">
                            <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-archive-accent opacity-75"></span>
                            <span class="relative inline-flex rounded-full h-6 w-6 bg-archive-accent text-archive-dark font-extrabold text-xs items-center justify-center shadow-lg border border-archive-paper">1</span>
                        </span>
                        <span class="hidden group-hover:block absolute bottom-full left-1/2 -translate-x-1/2 mb-2 px-2 py-1 bg-archive-dark text-archive-paper text-[10px] rounded whitespace-nowrap border border-archive-accent">Kawasan Alun-Alun / Kayutangan</span>
                    </button>

                    <!-- Interactive Pin 2 -->
                    <button onclick="selectMapLocation(1)" class="map-pin absolute top-[55%] left-[60%] transform -translate-x-1/2 -translate-y-1/2 group focus:outline-none">
                        <span class="relative flex h-6 w-6">
                            <span class="relative inline-flex rounded-full h-6 w-6 bg-archive-accent/80 text-archive-dark font-extrabold text-xs items-center justify-center shadow-lg border border-archive-paper">2</span>
                        </span>
                        <span class="hidden group-hover:block absolute bottom-full left-1/2 -translate-x-1/2 mb-2 px-2 py-1 bg-archive-dark text-archive-paper text-[10px] rounded whitespace-nowrap border border-archive-accent">Kawasan Celaket / Rampal</span>
                    </button>

                    <!-- Interactive Pin 3 -->
                    <button onclick="selectMapLocation(2)" class="map-pin absolute top-[40%] left-[30%] transform -translate-x-1/2 -translate-y-1/2 group focus:outline-none">
                        <span class="relative flex h-6 w-6">
                            <span class="relative inline-flex rounded-full h-6 w-6 bg-archive-accent/80 text-archive-dark font-extrabold text-xs items-center justify-center shadow-lg border border-archive-paper">3</span>
                        </span>
                        <span class="hidden group-hover:block absolute bottom-full left-1/2 -translate-x-1/2 mb-2 px-2 py-1 bg-archive-dark text-archive-paper text-[10px] rounded whitespace-nowrap border border-archive-accent">Stasiun Kereta Api Malang</span>
                    </button>
                </div>

                <!-- Location Info Panel Side Box -->
                <div class="lg:col-span-4 bg-archive-card border border-archive-border rounded-xl p-5 flex flex-col justify-between">
                    <div id="map-info-content">
                        <!-- Default Injected Info JS -->
                    </div>
                    <div class="text-[11px] text-archive-muted pt-4 border-t border-archive-border/60 italic">
                        * Titik geografis didasarkan pada perkiraan peta pemukiman dan pusat administrasi Malang abad ke-20.
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- SECTION 6: REFERENSI, SUMBER & PANDUAN PENGUNJUNG SEJARAH -->
    <section id="referensi" class="py-16 border-b border-archive-border bg-archive-dark">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-12 gap-8 items-start">
                
                <!-- Daftar Referensi Lengkap -->
                <div class="lg:col-span-7 space-y-6">
                    <div>
                        <div class="text-archive-accent text-xs font-bold tracking-widest uppercase mb-1">Akurasi & Transparansi</div>
                        <h2 class="font-cinzel text-2xl sm:text-3xl font-bold text-archive-paper">Daftar Referensi & Sumber Rujukan</h2>
                    </div>

                    <ul class="space-y-3 text-xs sm:text-sm text-archive-paper/80 font-sans">
                        <li class="p-3 bg-archive-card border border-archive-border rounded-lg flex items-start gap-3">
                            <i class="fa-solid fa-bookmark text-archive-accent mt-1"></i>
                            <div>
                                <strong>Koran De Locomotief (15 Februari 1927)</strong> — Artikel warta peringatan 25 tahun keberadaan Loge Malang (Halaman 3, Kolom 1).
                            </div>
                        </li>
                        <li class="p-3 bg-archive-card border border-archive-border rounded-lg flex items-start gap-3">
                            <i class="fa-solid fa-bookmark text-archive-accent mt-1"></i>
                            <div>
                                <strong>Kleian’s Adresboek van Geheel Nederlandsch-Indië (Edisi 1941)</strong> — Direktori pencatatan instansi dan perkumpulan kolonial.
                            </div>
                        </li>
                        <li class="p-3 bg-archive-card border border-archive-border rounded-lg flex items-start gap-3">
                            <i class="fa-solid fa-bookmark text-archive-accent mt-1"></i>
                            <div>
                                <strong>Stevens, Th. (1994)</strong> — <em>Vrijmetselarij en samenleving in Nederlands-Indië en Indonesië 1764-1962</em>. Uitgeverij Verloren, Hilversum.
                            </div>
                        </li>
                        <li class="p-3 bg-archive-card border border-archive-border rounded-lg flex items-start gap-3">
                            <i class="fa-solid fa-bookmark text-archive-accent mt-1"></i>
                            <div>
                                <strong>Widodo, Dukut Imam (2006)</strong> — <em>Malang Tempo Doeloe</em>. Katalogis & Perpustakaan UNIKA Widya Karya.
                            </div>
                        </li>
                    </ul>
                </div>

                <!-- Callout Box: Rekomendasi Kunjungan Perpustakaan & Arsip Daerah Malang -->
                <div class="lg:col-span-5 bg-gradient-to-br from-archive-card to-archive-dark border-2 border-archive-accent/60 rounded-2xl p-6 shadow-2xl relative overflow-hidden">
                    <div class="absolute -right-10 -bottom-10 opacity-10 text-archive-accent">
                        <i class="fa-solid fa-building-columns text-9xl"></i>
                    </div>

                    <div class="relative z-10 space-y-4">
                        <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-archive-accent/20 text-archive-accent text-xs font-bold uppercase">
                            <i class="fa-solid fa-location-dot"></i> Pendalaman Riset
                        </div>

                        <h3 class="font-cinzel text-xl font-bold text-archive-paper">Tertarik Menelusuri Lebih Lanjut?</h3>

                        <p class="text-sm text-archive-paper/90 leading-relaxed font-serif">
                            Apabila Anda ingin mempelajari lebih dalam mengenai manuskrip asli, catatan administrasi kota, dan koleksi fisik sejarah Malang tempo dulu, Anda sangat disarankan untuk mengunjungi langsung lembaga arsip resmi lokal:
                        </p>

                        <div class="space-y-3 pt-2 text-xs text-archive-paper/80">
                            <div class="flex items-start gap-2 bg-archive-bg/80 p-3 rounded border border-archive-border">
                                <i class="fa-solid fa-landmark text-archive-accent mt-0.5"></i>
                                <div>
                                    <strong class="text-archive-paper block">Dinas Perpustakaan Umum Kota Malang</strong>
                                    <span>Jl. Besar Ijen No. 30, Oro-oro Dowo, Kec. Klojen, Kota Malang</span>
                                </div>
                            </div>
                            <div class="flex items-start gap-2 bg-archive-bg/80 p-3 rounded border border-archive-border">
                                <i class="fa-solid fa-box-archive text-archive-accent mt-0.5"></i>
                                <div>
                                    <strong class="text-archive-paper block">Arsip Daerah Kota Malang</strong>
                                    <span>Pusat Layanan Dokumentasi Warta & Naskah Kuno Malang</span>
                                </div>
                            </div>
                        </div>

                        <div class="pt-2 text-xs text-archive-accent/90 italic">
                            "Menjaga dan mempelajari memori kolektif sejarah adalah bagian dari melestarikan identitas bangsa."
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-archive-bg border-t border-archive-border py-10 text-archive-paper/60 text-xs">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-4">
            <div class="flex items-center justify-center gap-3">
                <i class="fa-solid fa-compass-drafting text-archive-accent text-xl"></i>
                <span class="font-cinzel text-archive-accent font-bold text-base tracking-wider">MUSEUM DIGITAL FREEMASON MALANG</span>
            </div>
            <p class="max-w-xl mx-auto">
                Portal edukasi dan pusat studi sejarah independen non-profit. Dipersembahkan untuk pembelajaran akademis, penelitian budaya, dan dokumentasi sejarah lokal Kota Malang.
            </p>
            <div class="pt-4 border-t border-archive-border/40 text-[11px] text-archive-muted">
                &copy; 2026 Jejak Freemason di Malang — Pusat Dokumentasi Digital. Hak Cipta Dilindungi.
            </div>
        </div>
    </footer>

    <!-- MODAL DETAIL ARSIP / LIGHTBOX VIEWER -->
    <div id="detail-modal" class="fixed inset-0 z-50 bg-black/90 backdrop-blur-sm hidden flex items-center justify-center p-4">
        <div class="bg-archive-card border border-archive-border rounded-2xl max-w-3xl w-full max-h-[90vh] overflow-y-auto p-6 relative shadow-2xl space-y-4">
            <button onclick="closeModal()" class="absolute top-4 right-4 w-8 h-8 rounded-full bg-archive-dark border border-archive-border text-archive-paper hover:text-archive-accent flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="modal-content">
                <!-- Dynamic Modal Content -->
            </div>
        </div>
    </div>

    <!-- MODAL UNGGAH ARSIP (ADMIN / KONTRIBUSI PENGUNJUNG) -->
    <div id="upload-modal" class="fixed inset-0 z-50 bg-black/90 backdrop-blur-sm hidden flex items-center justify-center p-4">
        <div class="bg-archive-card border border-archive-border rounded-2xl max-w-lg w-full p-6 relative shadow-2xl space-y-4">
            <button onclick="closeUploadModal()" class="absolute top-4 right-4 w-8 h-8 rounded-full bg-archive-dark border border-archive-border text-archive-paper hover:text-archive-accent flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
            
            <div class="border-b border-archive-border/80 pb-3">
                <h3 class="font-cinzel font-bold text-archive-paper text-lg">Unggah Dokumen / Foto Arsip</h3>
                <p class="text-xs text-archive-paper/60">Ajukan kontribusi materi sejarah untuk dikaji oleh pengelola museum.</p>
            </div>

            <form onsubmit="handleUploadSubmit(event)" class="space-y-3 text-xs">
                <div>
                    <label class="block text-archive-paper font-semibold mb-1">Judul Dokumen / Foto:</label>
                    <input type="text" required placeholder="Contoh: Foto Gedung Kolonial Kayutangan 1930" class="w-full bg-archive-bg border border-archive-border rounded p-2 text-archive-paper focus:outline-none focus:border-archive-accent">
                </div>
                <div class="grid grid-cols-2 gap-3">
                    <div>
                        <label class="block text-archive-paper font-semibold mb-1">Tahun Perkiraan:</label>
                        <input type="text" required placeholder="Contoh: 1925" class="w-full bg-archive-bg border border-archive-border rounded p-2 text-archive-paper focus:outline-none focus:border-archive-accent">
                    </div>
                    <div>
                        <label class="block text-archive-paper font-semibold mb-1">Kategori:</label>
                        <select class="w-full bg-archive-bg border border-archive-border rounded p-2 text-archive-paper focus:outline-none focus:border-archive-accent">
                            <option>Foto Bangunan / Gedung</option>
                            <option>Koran / Surat Kabar Lama</option>
                            <option>Surat & Dokumen Resmi</option>
                            <option>Peta & Denah Sejarah</option>
                        </select>
                    </div>
                </div>
                <div>
                    <label class="block text-archive-paper font-semibold mb-1">Deskripsi & Sumber Dokumentasi:</label>
                    <textarea rows="3" required placeholder="Sebutkan asal usul berkas atau keterangan tempat..." class="w-full bg-archive-bg border border-archive-border rounded p-2 text-archive-paper focus:outline-none focus:border-archive-accent"></textarea>
                </div>
                <div>
                    <label class="block text-archive-paper font-semibold mb-1">Pilih Berkas (Gambar/PDF):</label>
                    <input type="file" required class="w-full bg-archive-bg border border-archive-border rounded p-1.5 text-archive-paper/80 file:mr-3 file:py-1 file:px-2 file:rounded file:border-0 file:bg-archive-accent file:text-archive-dark file:font-bold">
                </div>
                <div class="pt-2">
                    <button type="submit" class="w-full py-2.5 rounded bg-archive-accent text-archive-dark font-bold hover:bg-archive-accentHover transition-colors">
                        <i class="fa-solid fa-paper-plane mr-1"></i> Kirimkan Kontribusi Arsip
                    </button>
                </div>
            </form>
        </div>
    </div>

    <!-- JAVASCRIPT LOGIC & DATABASE DATA SIMULATION -->
    <script>
        // Database Data Koleksi Foto & Arsip Digital
        const collectionsData = [
            // Gambar 1 / Arsip Dokumen 1
            {
                id: 'arsip-1',
                type: 'arsip',
                title: 'Dokumen Sejarah Administrasi Kolonial Malang',
                year: 1915,
                category: 'Dokumen Sejarah',
                image: 'https://perpustakaankarmelindo.org/lib/minigalnano/createthumb.php?filename=images/docs/11.755..jpg&width=200',
                status: 'Sangat Baik (Arsip Digital)',
                description: 'Berkas catatan administrasi umum dan Korespondensi antar-organisasi di Malang era awal abad ke-20.',
                source: 'Koleksi Dokumentasi Arsip Sejarah Malang (Gambar 1)',
                verified: true
            },
            // Gambar 2 / Kleian's Adresboek 1941
            {
                id: 'arsip-2',
                type: 'arsip',
                title: 'Kleian’s Adresboek van Geheel Nederlandsch-Indië (1941)',
                year: 1941,
                category: 'Buku Direktori Kolonial',
                image: 'https://www.boudewynvanoort.com/wp-content/uploads/2016/03/Adresboekvan-Bandoeng-626x1024.jpg',
                description: 'Buku direktori Hindia Belanda ini disebut dalam penelitian sejarah sebagai salah satu sumber untuk menelusuri organisasi dan alamat pada masa kolonial. Entri khusus Loji Malang dalam edisi 1941 masih merupakan petunjuk pencarian, bukan bukti langsung yang sudah terkonfirmasi.',
                source: 'Rujukan Direktori Hindia Belanda 1941 (Gambar 2)',
                verified: false
            },
            // Gambar 3 / De Locomotief 15 Feb 1927
            {
                id: 'arsip-3',
                type: 'arsip',
                title: 'Koran De Locomotief — Edisi 15 Februari 1927',
                year: 1927,
                category: 'Surat Kabar Kolonial',
                image: 'https://bandungbergerak.id/cdn/7/1/7/0/7170.jpg',
                status: 'Petunjuk Koran Lama (Perlu Verifikasi Teks)',
                description: 'Sumber sejarah berbahasa Belanda mencatat bahwa Loji Freemason Malang telah berusia 25 tahun pada 1927 dan merujuk pada koran De Locomotief, edisi 15 Februari 1927, halaman 3 kolom 1. Ini petunjuk arsip yang spesifik, tetapi isi artikel koran aslinya belum berhasil dipastikan secara utuh.',
                source: 'Delpher / Pers Kolonial Belanda (Gambar 3)',
                verified: false
            },
            // Foto Bangunan 1
            {
                id: 'foto-1',
                type: 'foto',
                title: 'Lanskap Bangunan Kolonial Malang Tempo Dulu',
                year: 1920,
                location: 'Kawasan Kayutangan / Klojen, Malang',
                category: 'Bangunan Bersejarah',
                image: 'https://lppm.petra.ac.id/wp-content/uploads/2023/11/perkembangan-kota-scaled.jpg',
                description: 'Dokumentasi visual arsitektur gaya Indis di Malang pada dekade 1920-an, menunjukkan struktur facade simetris khas era kolonial.',
                source: 'Arsip Foto Publik Kota Malang',
                verified: true
            },
            // Foto Bangunan 2
            {
                id: 'foto-2',
                type: 'foto',
                title: 'Suasana Jalanan & Perkumpulan Warga Malang',
                year: 1935,
                location: 'Jalan Besar Ijen, Malang',
                category: 'Kegiatan Kolonial',
                image: 'https://tugumalang.id/wp-content/uploads/2021/10/28ec7c16-7e8e-4b47-bfa6-4d7f98369d7a.webp',
                description: 'Pemandangan lanskap kota dengan pepohonan palem ikonik dan aktivitas masyarakat urban Malang pra-Perang Dunia II.',
                source: 'Koleksi Dokumentasi Wilayah Jawa Timur',
                verified: true
            },
            // Peta Lama
            {
                id: 'arsip-4',
                type: 'arsip',
                title: 'Peta Wilayah & Tata Ruang Kota Malang (Topografisch Bureau)',
                year: 1925,
                category: 'Peta Wilayah Tempo Dulu',
                image: 'https://www.anjani.id/wp-content/uploads/2023/10/WhatsApp-Image-2023-10-26-at-11.13.06-PM-980x832.jpeg',
                status: 'Terverifikasi (Peta Resmi Belanda)',
                description: 'Peta zonasi pemukiman Eropa, Jawa, dan Pecinan di Malang yang memperlihatkan alokasi gedung-gedung publik dan fasilitas sosial.',
                source: 'Topografisch Bureau Nederlandsch-Indië',
                verified: true
            }
        ];

        // Data Titik Peta Sejarah Interaktif
        const mapLocations = [
            {
                name: 'Kawasan Kayutangan (Pusat Aktivitas Sosial)',
                year: '1900 - 1940',
                desc: 'Pusat komersial dan ruang berkumpulnya berbagai perhimpunan masyarakat Eropa dan elite lokal di Malang.',
                img: 'https://binus.ac.id/malang/dkv/wp-content/uploads/sites/9/2024/03/42-20231102095419-13961295776543B81BC6EA9.jpeg',
                source: 'Arsip Tata Kota Malang'
            },
            {
                name: 'Kawasan Celaket / Rampal',
                year: '1910 - 1930',
                desc: 'Area militer dan pemukiman pejabat kolonial di mana beberapa tokoh perhimpunan pernah memegang peranan administrasi.',
                img: 'https://upload.wikimedia.org/wikipedia/commons/5/55/COLLECTIE_TROPENMUSEUM_Huizen_aan_de_Tjelaket_in_Malang_TMnr_10023701.jpg?utm_source=id.wikipedia.org&utm_campaign=imageinfo&utm_content=thumbnail_unscaled',
                source: 'Catatan Wilayah Malang'
            },
            {
                name: 'Stasiun Kereta Api Malang (Transportasi Utama)',
                year: '1901',
                desc: 'Jalur konektivitas vital yang menghubungkan loge-loge Freemason Malang dengan Loge induk De Vriendschap di Surabaya.',
                img: 'https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhUS9ZaYPc2_TTXs8ChnqWQEDxqKFxH0g5QGIJD-t5RVAlKWNqNWmpfVCZrZe37wvP2cGynGtHbZhmtNCvoP2uoCwpkckkyAnoChnLird1tdvt8uVqdrOEkPWA3eHzkyDk4v1gesu4wdTE/s320/DSCF7539.JPG',
                source: 'Dokumentasi Staatsspoorwegen'
            }
        ];

        let selectedYearFilter = 'all';

        // Render Galeri Foto & Arsip Digital saat pertama dimuat
        document.addEventListener('DOMContentLoaded', () => {
            renderGallery();
            renderArchives();
            selectMapLocation(0);

            // Toggle Mobile Navigation Menu
            const mobileBtn = document.getElementById('mobile-menu-btn');
            const mobileMenu = document.getElementById('mobile-menu');
            mobileBtn.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });

            // Auto close mobile menu on item click
            document.querySelectorAll('.mobile-link').forEach(link => {
                link.addEventListener('click', () => {
                    mobileMenu.classList.add('hidden');
                });
            });
        });

        // Function Render Galeri Foto
        function renderGallery(searchTerm = '') {
            const container = document.getElementById('gallery-grid');
            container.innerHTML = '';

            const filtered = collectionsData.filter(item => {
                const isTypeMatch = item.type === 'foto';
                const isSearchMatch = item.title.toLowerCase().includes(searchTerm.toLowerCase()) || 
                                      item.description.toLowerCase().includes(searchTerm.toLowerCase());
                const isYearMatch = checkYearMatch(item.year);
                return isTypeMatch && isSearchMatch && isYearMatch;
            });

            if (filtered.length === 0) {
                container.innerHTML = `<div class="col-span-full py-10 text-center text-archive-muted text-sm italic">Tidak ada foto koleksi yang sesuai dengan kriteria pencarian.</div>`;
                return;
            }

            filtered.forEach(item => {
                const card = document.createElement('div');
                card.className = 'bg-archive-card border border-archive-border rounded-xl overflow-hidden hover:border-archive-accent transition-all duration-300 flex flex-col justify-between group shadow-lg';
                card.innerHTML = `
                    <div>
                        <div class="relative overflow-hidden h-48 bg-archive-dark">
                            <img src="${item.image}" alt="${item.title}" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 filter sepia-[0.2]">
                            <span class="absolute top-3 right-3 bg-archive-dark/90 text-archive-accent text-[10px] font-bold px-2 py-0.5 rounded border border-archive-border">
                                ${item.year}
                            </span>
                        </div>
                        <div class="p-4 space-y-2">
                            <span class="text-[10px] text-archive-accent font-semibold uppercase tracking-wider">${item.category}</span>
                            <h3 class="font-serif font-bold text-archive-paper text-sm line-clamp-1">${item.title}</h3>
                            <p class="text-xs text-archive-paper/70 line-clamp-2 leading-relaxed">${item.description}</p>
                        </div>
                    </div>
                    <div class="p-4 pt-0 text-xs flex justify-between items-center border-t border-archive-border/40 mt-3">
                        <span class="text-[11px] text-archive-muted italic truncate max-w-[150px]"><i class="fa-solid fa-location-dot mr-1"></i>${item.location || 'Malang'}</span>
                        <button onclick="openDetailModal('${item.id}')" class="text-xs text-archive-accent hover:underline font-semibold flex items-center gap-1">
                            Detail <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                `;
                container.appendChild(card);
            });
        }

        // Function Render Arsip Digital
        function renderArchives(searchTerm = '') {
            const container = document.getElementById('archive-grid');
            container.innerHTML = '';

            const filtered = collectionsData.filter(item => {
                const isTypeMatch = item.type === 'arsip';
                const isSearchMatch = item.title.toLowerCase().includes(searchTerm.toLowerCase()) || 
                                      item.description.toLowerCase().includes(searchTerm.toLowerCase());
                const isYearMatch = checkYearMatch(item.year);
                return isTypeMatch && isSearchMatch && isYearMatch;
            });

            if (filtered.length === 0) {
                container.innerHTML = `<div class="col-span-full py-10 text-center text-archive-muted text-sm italic">Tidak ada dokumen arsip yang sesuai dengan kriteria.</div>`;
                return;
            }

            filtered.forEach(item => {
                const card = document.createElement('div');
                card.className = 'bg-archive-card border border-archive-border rounded-xl overflow-hidden hover:border-archive-accent transition-all duration-300 flex flex-col justify-between p-5 shadow-lg';
                
                const badgeVerified = item.verified 
                    ? `<span class="bg-emerald-900/40 text-emerald-300 border border-emerald-700/50 text-[10px] px-2 py-0.5 rounded font-semibold"><i class="fa-solid fa-check mr-1"></i>Terverifikasi</span>`
                    : `<span class="bg-amber-900/50 text-amber-300 border border-amber-700/50 text-[10px] px-2 py-0.5 rounded font-semibold"><i class="fa-solid fa-magnifying-glass mr-1"></i>Petunjuk Pencarian</span>`;

                card.innerHTML = `
                    <div class="space-y-3">
                        <div class="flex items-center justify-between">
                            <span class="text-[10px] text-archive-accent font-mono uppercase tracking-wider">${item.category}</span>
                            ${badgeVerified}
                        </div>
                        <h3 class="font-serif font-bold text-archive-paper text-base leading-snug">${item.title}</h3>
                        <div class="h-32 rounded bg-archive-dark border border-archive-border overflow-hidden relative">
                            <img src="${item.image}" alt="${item.title}" class="w-full h-full object-cover opacity-80 filter contrast-110">
                        </div>
                        <p class="text-xs text-archive-paper/80 leading-relaxed line-clamp-3">${item.description}</p>
                    </div>
                    <div class="mt-4 pt-3 border-t border-archive-border/60 flex items-center justify-between">
                        <span class="text-[11px] text-archive-muted font-mono"><i class="fa-solid fa-calendar mr-1"></i>${item.year}</span>
                        <button onclick="openDetailModal('${item.id}')" class="px-3 py-1 bg-archive-accent/10 border border-archive-accent/40 rounded text-archive-accent text-xs hover:bg-archive-accent hover:text-archive-dark transition-all font-semibold">
                            Buka Berkas
                        </button>
                    </div>
                `;
                container.appendChild(card);
            });
        }

        // Helper filter tahun
        function checkYearMatch(year) {
            if (selectedYearFilter === 'all') return true;
            if (selectedYearFilter === '1900') return year >= 1900 && year <= 1920;
            if (selectedYearFilter === '1920') return year >= 1921 && year <= 1940;
            if (selectedYearFilter === '1940') return year >= 1941;
            return true;
        }

        function setYearFilter(yearKey) {
            selectedYearFilter = yearKey;
            document.querySelectorAll('.filter-btn').forEach(btn => {
                btn.classList.remove('bg-archive-accent', 'text-archive-dark', 'active');
                btn.classList.add('bg-archive-card', 'text-archive-paper');
            });
            event.target.classList.add('bg-archive-accent', 'text-archive-dark', 'active');
            
            const searchValue = document.getElementById('global-search').value;
            renderGallery(searchValue);
            renderArchives(searchValue);
        }

        function filterGlobalCollections() {
            const searchValue = document.getElementById('global-search').value;
            renderGallery(searchValue);
            renderArchives(searchValue);
        }

        // Detail Modal Lightbox Opener
        function openDetailModal(id) {
            const item = collectionsData.find(c => c.id === id);
            if (!item) return;

            const modalContent = document.getElementById('modal-content');
            modalContent.innerHTML = `
                <div class="space-y-4">
                    <div class="flex items-center justify-between border-b border-archive-border/80 pb-3">
                        <span class="text-xs font-mono text-archive-accent uppercase font-bold tracking-widest">${item.category} • Tahun ${item.year}</span>
                        ${item.verified 
                            ? `<span class="bg-emerald-900/60 text-emerald-200 text-xs px-2.5 py-0.5 rounded font-semibold">Status: Terverifikasi</span>`
                            : `<span class="bg-amber-900/60 text-amber-200 text-xs px-2.5 py-0.5 rounded font-semibold">Status: Petunjuk Pencarian</span>`}
                    </div>

                    <h2 class="font-cinzel text-xl sm:text-2xl font-bold text-archive-paper">${item.title}</h2>

                    <div class="rounded-xl overflow-hidden border border-archive-border max-h-[350px] bg-black">
                        <img src="${item.image}" alt="${item.title}" class="w-full h-full object-contain mx-auto">
                    </div>

                    <div class="space-y-2 text-xs sm:text-sm text-archive-paper/90 leading-relaxed font-sans">
                        <h4 class="font-bold text-archive-accent uppercase text-xs">Deskripsi & Catatan Sejarah:</h4>
                        <p class="bg-archive-dark p-3.5 rounded border border-archive-border/60">${item.description}</p>
                    </div>

                    <div class="grid sm:grid-cols-2 gap-3 text-xs bg-archive-bg p-3 rounded border border-archive-border">
                        <div>
                            <span class="text-archive-muted block">Sumber Dokumentasi:</span>
                            <span class="text-archive-paper font-semibold">${item.source}</span>
                        </div>
                        <div>
                            <span class="text-archive-muted block">Status Keberadaan Arsip:</span>
                            <span class="text-archive-paper font-semibold">${item.status || 'Tersedia Digital'}</span>
                        </div>
                    </div>

                    <div class="pt-2 flex justify-end gap-3">
                        <button onclick="closeModal()" class="px-4 py-2 rounded bg-archive-dark border border-archive-border text-archive-paper text-xs hover:bg-archive-card">Tutup Window</button>
                        <button onclick="alert('Mengunduh pratinjau dokumen arsip resolusi standar...')" class="px-4 py-2 rounded bg-archive-accent text-archive-dark font-bold text-xs hover:bg-archive-accentHover flex items-center gap-1.5">
                            <i class="fa-solid fa-download"></i> Unduh Salinan Digital
                        </button>
                    </div>
                </div>
            `;

            document.getElementById('detail-modal').classList.remove('hidden');
        }

        function closeModal() {
            document.getElementById('detail-modal').classList.add('hidden');
        }

        // Peta Sejarah Interaktif Selector
        function selectMapLocation(index) {
            const loc = mapLocations[index];
            const container = document.getElementById('map-info-content');
            
            container.innerHTML = `
                <div class="space-y-3">
                    <span class="bg-archive-accent/20 text-archive-accent text-[10px] font-bold px-2 py-0.5 rounded uppercase">Titik Lokasi #${index + 1}</span>
                    <h3 class="font-serif font-bold text-archive-paper text-lg">${loc.name}</h3>
                    <span class="text-xs text-archive-accent block font-mono"><i class="fa-solid fa-clock mr-1"></i>Era Penelusuran: ${loc.year}</span>
                    <div class="h-32 rounded-lg overflow-hidden border border-archive-border">
                        <img src="${loc.img}" alt="${loc.name}" class="w-full h-full object-cover">
                    </div>
                    <p class="text-xs text-archive-paper/80 leading-relaxed">${loc.desc}</p>
                    <div class="text-[11px] text-archive-muted border-t border-archive-border/40 pt-2">
                        Sumber: ${loc.source}
                    </div>
                </div>
            `;
        }

        // Admin Upload Modal Controls
        function openUploadModal() {
            document.getElementById('upload-modal').classList.remove('hidden');
        }

        function closeUploadModal() {
            document.getElementById('upload-modal').classList.add('hidden');
        }

        function handleUploadSubmit(e) {
            e.preventDefault();
            alert('Terima kasih! Kontribusi berkas arsip Anda telah terkirim dan akan ditinjau oleh tim kurator sejarah museum.');
            closeUploadModal();
        }
    </script>
</body>
</html>
