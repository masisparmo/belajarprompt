Dokumentasi Aplikasi: Seni Memerintah AI untuk UMKM
===================================================

Dokumen ini memberikan gambaran menyeluruh tentang aplikasi web "Seni Memerintah AI untuk UMKM", sebuah platform pembelajaran interaktif yang dirancang untuk memberdayakan Usaha Mikro, Kecil, dan Menengah dengan keterampilan _prompt engineering_.

Aplikasi ini bisa diakses di https://belajarprompt.isparmo.com/

1\. Deskripsi Aplikasi
----------------------

**Seni Memerintah AI untuk UMKM** adalah sebuah aplikasi web _client-side_ yang berfungsi sebagai pusat pembelajaran lengkap untuk menguasai seni berkomunikasi dengan kecerdasan buatan (AI). Aplikasi ini didasarkan pada ebook "Seni Memerintah AI" dan dirancang untuk memberikan pengalaman belajar yang praktis dan tidak hanya teoretis.

Tujuan utamanya adalah untuk mendemistifikasi teknologi AI dan menjadikannya alat yang dapat diakses oleh para pelaku UMKM untuk meningkatkan efisiensi pemasaran, penjualan, layanan pelanggan, dan operasional bisnis secara keseluruhan.

Fitur utama aplikasi meliputi:

*   **Materi Interaktif:** Ringkasan ebook yang disajikan dalam format akordeon yang mudah dicerna.
    
*   **Ebook Reader:** Tampilan _embedded_ dari ebook lengkap untuk dibaca langsung.
    
*   **Playground:** Area praktik di mana pengguna dapat langsung mencoba prompt untuk menghasilkan teks atau gambar, dilengkapi dengan **Asisten Prompt** untuk memandu pemula.
    
*   **Tanya Ahli:** Chatbot yang bertindak sebagai Ahli Prompt Engineering di mana pengguna dapat bertanya tentang _prompt engineering_ kepada asisten AI.
    
*   **Kuis Dinamis:** Fitur evaluasi di mana soal-soal kuis dibuat secara _real-time_ oleh AI, memastikan setiap sesi kuis unik.
    

2\. Teknologi yang Digunakan
----------------------------

Aplikasi ini sepenuhnya berjalan di sisi pengguna (_client-side_), yang berarti tidak memerlukan _backend_ atau server khusus, sehingga ideal untuk di-hosting di layanan gratis seperti GitHub Pages.

*   **Struktur & Tampilan:**
    
    *   **HTML5:** Sebagai fondasi struktur halaman web.
        
    *   **Tailwind CSS:** Kerangka kerja CSS modern untuk membangun antarmuka yang responsif dan menarik dengan cepat.
        
    *   **Lucide Icons:** Pustaka ikon yang ringan dan konsisten untuk memperjelas navigasi dan tombol.
        
*   **Fungsionalitas & Interaktivitas:**
    
    *   **JavaScript (ES6+):** Menjadi otak dari semua fitur interaktif, mulai dari navigasi tab, logika Asisten Prompt, hingga pemanggilan API.
        
*   **Kecerdasan Buatan (AI):**
    
    *   **Google Gemini API:** Jantung dari semua fitur cerdas di aplikasi ini.
        
        *   **gemini-2.5-flash-preview-05-20:** Digunakan untuk semua tugas yang berhubungan dengan generasi teks, seperti pada fitur Tanya Ahli, Analisis Prompt, dan pembuatan soal Kuis.
            
        *   **gemini-2.0-flash-preview-image-generation:** Digunakan khusus pada fitur Playground untuk mengubah prompt teks menjadi gambar. Model ini dipilih karena dapat diakses menggunakan API key standar tanpa memerlukan akun berbayar.
            

3\. Target Pengguna
-------------------

Aplikasi ini dirancang untuk audiens yang luas, namun secara spesifik menargetkan:

1.  **Pemilik UMKM:** Pelaku usaha yang ingin memanfaatkan AI untuk menghemat waktu dan biaya dalam membuat konten pemasaran, deskripsi produk, dan strategi bisnis tanpa harus merekrut tim khusus.
    
2.  **Staf Pemasaran & Media Sosial:** Profesional yang bertanggung jawab atas konten digital dan ingin meningkatkan kualitas serta kuantitas output kreatif mereka.
    
3.  **Mahasiswa & Pelajar:** Individu yang tertarik mempelajari aplikasi praktis dari teknologi AI di dunia bisnis.
    
4.  **Siapa Saja yang Ingin Belajar AI:** Pengguna umum yang penasaran dengan _prompt engineering_ dan ingin belajar melalui platform yang terstruktur dan interaktif.
    

4\. Cara Menggunakan Aplikasi
-----------------------------

Berikut adalah panduan langkah demi langkah untuk menggunakan aplikasi ini secara maksimal.

**Langkah 1: Dapatkan Google AI API Key**Aplikasi ini memerlukan API Key agar fitur-fitur cerdasnya dapat berfungsi.

*   Kunjungi **Google AI Studio** di aistudio.google.com.
    
*   Login dengan akun Google Anda.
    
*   Cari dan klik tombol **"Get API key"**, lalu pilih **"+ Create API key in new project"**.
    
*   Salin (copy) API key yang muncul.
    

**Langkah 2: Memulai Aplikasi**

*   Saat pertama kali membuka aplikasi, sebuah modal akan muncul.
    
*   Tempel (paste) API key yang sudah Anda salin ke dalam kolom **"Opsi 1: Gunakan API Key Sendiri"**.
    
*   Klik **"Jalankan Aplikasi"**.
    

**Langkah 3: Jelajahi Fitur Utama**

*   **Beranda:** Halaman sambutan dengan navigasi cepat ke fitur lain.
    
*   **Materi:** Pelajari ringkasan setiap bab dari ebook dalam format yang mudah dibaca.
    
*   **Ebook:** Baca versi lengkap dari ebook "Seni Memerintah AI".
    
*   **Tanya Ahli:** Ajukan pertanyaan apa pun seputar _prompt engineering_ dan dapatkan jawaban langsung dari AI.
    
*   **Kuis:** Uji pemahaman Anda dengan soal-soal yang dibuat secara dinamis oleh AI.
    

**Langkah 4: Praktik di Playground dengan Asisten Prompt**Playground adalah area terpenting untuk praktik.

1.  Klik tab **Playground**.
    
2.  Untuk pemula, klik tombol **"Asisten Prompt"**.
    
3.  **Isi formulir Asisten:**
    
    *   **Konteks Bisnis:** Masukkan detail tentang brand Anda. Semakin lengkap, semakin baik hasilnya.
        
    *   **Detail Tugas:** Pilih tujuan spesifik Anda dari dropdown. Formulir akan menampilkan kolom-kolom tambahan yang relevan. Isi semua detail yang diminta.
        
4.  Klik **"Buat & Salin Prompt"**. Asisten akan secara otomatis menyusun prompt yang sangat detail dan memasukkannya ke dalam kotak teks utama.
    
5.  Pilih **Mode Output** ("Teks" atau "Gambar").
    
6.  Klik **"Kirim"** untuk melihat hasilnya.
    

5\. Cara Hosting di GitHub Pages
--------------------------------

Karena aplikasi ini hanya terdiri dari satu file HTML, proses hosting-nya sangat mudah.

1.  **Prasyarat:** Anda memerlukan akun [GitHub](https://github.com/) dan [Git](https://git-scm.com/downloads) yang sudah terinstal di komputer Anda.
    
2.  **Buat Repository Baru:**
    
    *   Di akun GitHub Anda, buat sebuah repository baru. Beri nama, misalnya seni-memerintah-ai.
        
    *   Pastikan repository diatur sebagai **Public**.
        
3.  **Siapkan File Aplikasi:**
    
    *   Simpan seluruh kode aplikasi ke dalam satu file bernama index.html.
        
4.  **Unggah File ke GitHub:**
    
    *   Buka terminal atau command prompt di komputer Anda.
        
    *   Navigasi ke folder tempat Anda menyimpan file index.html.
        
    *   git initgit add index.htmlgit commit -m "Initial commit"git branch -M maingit remote add origin https://github.com/USERNAME/REPOSITORY\_NAME.gitgit push -u origin main
        
5.  **Aktifkan GitHub Pages:**
    
    *   Di halaman repository GitHub Anda, buka tab **"Settings"**.
        
    *   Di menu sebelah kiri, pilih **"Pages"**.
        
    *   Pada bagian "Branch", pilih branch main dan biarkan folder /root. Klik **"Save"**.
        
6.  **Selesai!**
    
    *   GitHub akan memberikan Anda sebuah URL (contoh: https://USERNAME.github.io/REPOSITORY\_NAME/).
        
    *   Tunggu beberapa menit, lalu akses URL tersebut. Aplikasi Anda kini sudah online.
        

6\. Lima Ide Pengembangan Fitur
-------------------------------

Berikut adalah lima ide fitur yang dapat diimplementasikan di masa depan untuk memperkaya aplikasi ini:

1.  **Studi Kasus Interaktif:** Membuat halaman berisi tantangan bisnis UMKM fiktif. Pengguna diberi tugas untuk memperbaiki _template_ prompt yang kurang efektif dan langsung melihat perbandingan hasilnya, memberikan pengalaman belajar berbasis masalah.
    
2.  **Galeri Prompt UMKM:** Sebuah "buku resep" berisi koleksi prompt siap pakai yang dikategorikan berdasarkan kebutuhan bisnis (misal: Pemasaran, Layanan Pelanggan). Setiap prompt disertai contoh hasil dan penjelasan, memberikan inspirasi instan bagi pengguna.
    
3.  **Simulasi Chat Layanan Pelanggan:** Fitur latihan di mana AI berperan sebagai pelanggan dengan berbagai skenario (komplain, bertanya, dll.). Pengguna bertugas merespons, dan AI akan memberikan evaluasi serta melanjutkan percakapan, melatih keterampilan komunikasi secara praktis.
    
4.  **Penyimpanan Riwayat Lokal (localStorage):** Menggunakan localStorage browser untuk menyimpan riwayat percakapan di "Tanya Ahli" dan prompt terakhir di "Playground". Ini mencegah pengguna kehilangan pekerjaan mereka jika tidak sengaja menutup tab, meningkatkan kenyamanan penggunaan.
    
5.  **Analisis Gambar Produk:** Fitur canggih di mana pengguna dapat mengunggah foto produk mereka. AI kemudian akan memberikan analisis (misal: "pencahayaan kurang baik", "latar belakang terlalu ramai") dan secara otomatis membuat beberapa alternatif deskripsi produk atau caption media sosial berdasarkan gambar tersebut.
