<div align="center">

# Athaillah Nazhif (Najib) Firdaus

<p>
  <b>Founder & Systems Architect at Naverse Group</b> • Creative Technologist & Systems Engineer<br>
  Jakarta, Indonesia
</p>

<p>
  <a href="https://anf-portfolio.vercel.app/">
    <img src="https://img.shields.io/badge/Status-●_Available_for_Work_&_Mentoring-2ea44f?style=flat-square" alt="Status" />
  </a>
  <a href="https://anf-portfolio.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-anf--portfolio.vercel.app-0969da?style=flat-square" alt="Portfolio" />
  </a>
  <a href="mailto:azhif.firdaus25@gmail.com">
    <img src="https://img.shields.io/badge/Email-azhif.firdaus25@gmail.com-d97706?style=flat-square" alt="Email" />
  </a>
</p>

<p>
  <a href="https://www.linkedin.com/in/athaillahnazhif/">
    <img src="https://img.shields.io/badge/LinkedIn-athaillahnazhif-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://wa.me/6282125511485">
    <img src="https://img.shields.io/badge/WhatsApp-Direct_Chat-25d366?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>
  <a href="https://instagram.com/athnf._">
    <img src="https://img.shields.io/badge/Instagram-@athnf._-e4405f?style=flat-square&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</p>

</div>

---

### Executive Profile

Software engineer, systems architect, dan creative technologist berbasis di Jakarta, Indonesia. Pendiri **Naverse Group (Naverse Teknologi Utama)**, mengarahkan arsitektur produk perangkat lunak, infrastruktur platform digital, dan solusi sistem klien enterprise.

* **Academic Background:**
  * **Universitas Terbuka:** Bachelor of Computer Science (S.Kom), Information Systems, Fakultas Sains dan Teknologi.
  * **SMK Negeri 65 Jakarta ('25):** Diploma Kejuruan Rekayasa Perangkat Lunak (Nilai Kelulusan: 87.5).
* **Core Competencies & Engineering Focus:**
  * **High-Concurrency Systems & Embedded Kernels:** Perancangan arsitektur berlatensi rendah menggunakan eksekusi in-memory, kernel transaksi basis data terbenam SQLite 3 WAL berlatensi sub-15ms, dan sinkronisasi state machine via WebSocket waktu nyata.
  * **Zero-Trust Hardened Data Layers:** Penegakan keamanan data melalui PostgreSQL Row Level Security (RLS), stored procedures atomik, dan mitigasi menyeluruh terhadap kerentanan OWASP Top 10.
  * **Cinematography & Audio-Visual Production:** Penguasaan teknis pengoperasian kamera sinematik manual, penataan pencahayaan adegan, pengawasan kontinuitas visual (*visual continuity*), serta tata kelola pascaproduksi berbasis Adobe Creative Cloud.
  * **Cross-Disciplinary Leadership:** Memimpin kolaborasi lintas kejuruan teknik dan multimedia pada pameran teknologi berskala kementerian dan institusional.

---

### Ventures & Architecture Ecosystem (Naverse Group)

```
Naverse Teknologi Utama (Holding Entity)
├── Naverse Academy   [Live Flagship] : Concept-First EdTech Platform & CBT Exam Engine
├── Naverse Technology [Available]    : Enterprise Systems, Web Infrastructure & Game Server Engineering
└── Naverse Studio     [On Hiatus]    : 3D Standalone Games & Interactive Simulations (Formerly JzInteractive)
```

#### 1. Naverse Academy `[Live Flagship]`
* **Role:** Founder, Solo Developer & Lead Instructor
* **Target:** Menghilangkan kebiasaan menghafal sintaksis melalui pembelajaran konsep dasar komputasi berbasis diagram struktural, modul bacaan mendalam, dan *coding sandbox* terisolasi.
* **Architecture & Hardening:**
  * **Frontend & Runtime:** Next.js 16 (App Router), React 19, Tailwind CSS v4, tipografi ganda Poppins dan Plus Jakarta Sans.
  * **Database & Security:** Supabase PostgreSQL 17 dengan Row Level Security (RLS) ketat, trigger pencegah manipulasi profil (`trg_protect_profiles_secure`), dan stored procedures atomik.
  * **In-Browser Sandbox Engine:** Lingkungan eksekusi Python 3 dan JavaScript sisi klien tanpa dependensi eksternal, dilengkapi pembatas perulangan otomatis (*circuit breaker*) 20.000 iterasi untuk mencegah pembekuan peramban.
  * **UTBK-Standard CBT Anti-Cheat:** Penegakan mode layar penuh wajib, pemantauan status fokus jendela dan tab, diskualifikasi otomatis setelah akumulasi 3 pelanggaran, penguncian *clipboard*, kuota evaluasi minimum 5 soal, serta pembatalan sertifikat otomatis pada reset modul.
  * **Payment Integration:** Sistem penagihan multi-layer Mayar API v2 dengan rekonsiliasi webhook otomatis dan alokasi poin atomik.
  * **Navi AI Operational Assistant:** Asisten operasional berlatensi sub-40ms berbasis failover model ganda Groq, pembatas frekuensi panggilan (*sliding-window rate limiter* 5 permintaan per 30 detik), dan pertahanan anti-jailbreak 4 tingkat.

#### 2. Naverse Technology `[Available for Enterprise & Client Projects]`
* **Role:** Full-Stack Systems Engineer & Consultant
* **Scope:** Rekayasa sistem web berlatensi rendah, platform evaluasi mandiri, portal media massa enterprise, dan plugin server *game* multipemain berbasis Java.
* **Featured Production Systems:**
  * **Universal CBT Engine (CBTSMA20):**
    * Platform evaluasi asesmen Bring Your Own Device (BYOD) berbasis web murni tanpa ketergantungan aplikasi pihak ketiga, dibangun menggunakan Laravel 12 pada runtime PHP 8.2+ multi-worker.
    * Menggunakan kernel basis data transaksi mikro SQLite 3 mode Write-Ahead Logging (WAL) berlatensi tulis sub-15ms tanpa hambatan konkurensi (*lock contention*).
    * Dilengkapi telemetri proktor waktu nyata via daemon mandiri Laravel Reverb WebSocket (0ms push).
    * Matriks sensor integritas peramban native: HTML5 Page Visibility, auto-blackout buram seketika 0ms (`blur-24px`, `opacity-0.15`), pemantauan rasio layar belah Visual Viewport (<75%), dan Screen WakeLock.
    * Arsitektur persistensi ganda (localStorage dan IndexedDB) dengan antrean luring dan sinkronisasi tumpak (*batch sync*) otomatis saat koneksi pulih; terverifikasi melalui 16 skenario operasional terisolasi dan pengujian otomatis OWASP Top 10.
  * **Timesiana Enterprise News Portal (`news-naldstronaut`):**
    * Sistem portal media massa digital enterprise yang diterbitkan oleh **PT Komunikasi Pratama Nusantara**.
    * Dibangun dengan arsitektur PHP dan basis data MySQL berkinerja tinggi untuk mendukung lalu lintas pembaca berita berskala besar.
    * Dilengkapi modul otomatisasi redaksi terintegrasi Google Gemini API untuk peringkasan dan parafrase naskah berita instan.
    * Mesin monetisasi ganda terintegrasi Google AdSense dan sistem iklan *banner in-house* (slot header, in-article, dan sidebar).
    * Kepatuhan regulasi pers Indonesia: Menampung pedoman Dewan Pers (Kode Etik Jurnalistik, Pedoman Media Siber, Hak Jawab & Klarifikasi) serta injeksi terstruktur JSON-LD Schema.org NewsArticle untuk pengindeksan mesin pencari.
  * **SIABSENSI (PT Jaringan Putra Nusantara):**
    * Platform absensi GPS dan penggajian karyawan enterprise berbasis Laravel 10, MySQL, dan Tailwind CSS.
    * Dilengkapi verifikasi presensi lokasi GPS dan swafoto wajah waktu nyata, persetujuan cuti berjenjang, kalkulasi otomatis PPh 21 dan THR, serta otomasi penerbitan slip gaji format PDF tumpak.
  * **Portal Resmi OSIS & MPK SMKN 65 Jakarta (`ospk-modern`):**
    * Portal profil organisasi resmi berbasis Astro 5 Islands Architecture (Zero-JS baseline) dan Tailwind CSS v4 (kompiler Rust).
    * Memanfaatkan optimasi gambar otomatis WebP/AVIF via modul Sharp, antarmuka modular Bento Grid, dan skor performa Lighthouse 100.
  * **Airline Reservation Platform (ARS):**
    * Aplikasi reservasi tiket penerbangan berbasis Laravel lengkap dengan manajemen jadwal, kontrol otorisasi berbasis peran (RBAC), pencatatan log transaksi basis data, enkripsi data sensitif, dan pencadangan basis data terjadwal.
  * **E-VOTER (SMKN 65 Jakarta):**
    * Sistem pemilihan umum ketua OSIS dan MPK berbasis web menggunakan PHP, AJAX, Tailwind CSS, dan Bootstrap. Menangani proses pemungutan suara serentak ratusan siswa dengan validasi suara tunggal dan dasbor pemantauan hasil suara langsung.
  * **PMB Academic Admission System:**
    * Sistem registrasi penerimaan mahasiswa baru dilengkapi modul ujian saringan masuk CBT terintegrasi pembatasan sesi pengerjaan.
  * **Hydenia SMP S3: Production Server Architecture (Java 21 / PaperMC 1.21):**
    * Lima modul plugin server multipemain kustom yang dirancang dengan alokasi memori efisien tanpa penurunan laju detak server (*tick lag*):
      * **`ZevictCurse`:** Mesin kutukan *hardcore roleplay* dengan pelacakan status entitas dan penanganan event permainan kustom.
      * **`ZevictsVendetta`:** Sistem buronan (*wanted*) dan penetapan hadiah (*bounty*) PvP dinamis antarpemain dengan kalkulasi distribusi imbalan otomatis.
      * **`HydeniaScoreboard`:** Papan skor dinamis berbasis manipulasi paket jaringan nirkedip (*anti-flicker*) yang menyinkronkan status faksi dan catatan buronan.
      * **`HydeniaSecureTrade`:** Antarmuka GUI barter antarpemain aman berfitur verifikasi kunci ganda (*dual-lock confirmation*) dan pembatasan jarak fisik untuk mencegah manipulasi transaksi (*anti-scam*).
      * **`HydeniaAnchoredSpawnPlatform`:** Mesin penempatan area spawn acak dan teleportasi asinkron untuk menjamin kelancaran koneksi saat lonjakan pemain baru masuk ke dalam server.

#### 3. Naverse Studio `[On Hiatus]` *(Formerly JzInteractive on itch.io)*
* **Role:** Solo Game Developer & Creative Technologist
* **Scope:** Permainan 3D mandiri dan simulasi interaktif yang dibangun menggunakan Unity Universal Render Pipeline (URP), pemrograman C#, dan Blender.
* **Flagship Project:**
  * **ANOMALY FLOOR 0:** Permainan horor psikologis pencarian anomali 3D mandiri yang dirilis di itch.io. Dikembangkan mandiri dengan mekanika putaran prosedural, state machine karakter, logika transisi elevator, optimasi *occlusion culling* untuk stabilitas 60+ FPS, dan tata suara spasial 3D untuk Windows, macOS, dan Linux.

---

### Academic Research & Scientific Publications

* 📑 **Rekayasa Platform Evaluasi Computer-Based Testing Mandiri Berbasis Bring Your Own Device Menggunakan SQLite WAL dan Protokol Multi-Sensor Integritas Peramban**
  * **Penulis:** **Athaillah Nazhif Firdaus (Penulis Utama & Penulis Korespondensi)**, Muhammad Dhafin Haron (Politeknik STMI Jakarta).
  * **Institusi Afiliasi:** Program Studi Sistem Informasi, Fakultas Sains dan Teknologi, Universitas Terbuka, Indonesia.
  * **Target Publikasi:** [Jurnal Sains, Nalar, dan Aplikasi Teknologi Informasi (SNATI)](https://journal.uii.ac.id/jurnalsnati/index) — Jurusan Informatika, Fakultas Teknologi Industri, Universitas Islam Indonesia (UII).
  * **Target Akreditasi:** **SINTA 4** (ISSN Media Elektronik: 2807-5935).
  * **Status Naskah:** **Naskah Riset Terapan (Dalam Proses Penelaahan / Under Review — Belum Diterbitkan)**.
  * **Fokus Kontribusi Ilmiah:** Memecahkan masalah kegagalan konkurensi (HTTP 504) dan tingginya biaya lisensi perangkat lunak asesmen sekolah melalui arsitektur kernel SQLite 3 WAL berlatensi sub-15ms, penegakan integritas peramban multi-sensor (Page Visibility, 0ms auto-blackout, Visual Viewport), dan kepemilikan penuh kode sumber institusi (*non-SaaS digital sovereignty*).

---

### Creative Direction & Cinematography (Non-Software Production)

* 🎬 **Film Pendek Horor: "SIUL" (Film Praktik Karya Jurusan Broadcasting dan Perfilman / BCF SMKN 65 Jakarta)**
  * **Peran:** **Assistant Director of Photography 2 (Ass. DOP 2 / 2nd Assistant Camera)**
  * **Tanggung Jawab Teknis:**
    * Mengoperasikan kamera unit kedua dan mengatur pemasangan perlengkapan (*camera rigging*) di lokasi syuting.
    * Memantau dan memastikan kesinambungan adegan (*script & visual continuity*) mencakup kesesuaian posisi pemain, sudut kamera, dan tata cahaya antarpengambilan adegan (*takes*).
    * Mengatur pencahayaan pendukung (*lighting assist*) dan penyesuaian jarak fokus kamera pada adegan berintensitas cahaya rendah (*low-key horror lighting*).

---

### Leadership, Multidisciplinary Collaborations & Expos

* 🏛️ **65Creativity (Organisasi Resmi Pameran & Showcase Multimedia SMKN 65 Jakarta)**
  * **Peran:** **Perwakilan Utama Jurusan Rekayasa Perangkat Lunak (RPL)**
  * **Sinergi Lintas Bidang:** Mengoordinasikan integrasi perangkat lunak rekayasa sistem dengan karya visual dari jurusan Desain Komunikasi Visual (DKV) serta tata audio-visual dari jurusan Broadcasting dan Perfilman (BCF).
  * **Pameran Terpilih:**
    * **Pameran / Expo Kementerian Pendidikan di Monumen Nasional (Monas):** Memamerkan dan mendemonstrasikan aplikasi perangkat lunak interaktif buatan siswa langsung kepada pengunjung umum, komunitas pengembang, dan jajaran kementerian.
    * **Pameran / Expo Kolaborasi Kejuruan di SMK Negeri 26 Jakarta:** Mempresentasikan sistem digital terintegrasi dan demonstrasi rekayasa perangkat lunak dalam ajang temu pameran antar-SMK teknik unggulan DKI Jakarta.

---

### Technical Arsenal & Creative Toolset

| Domain | Teknologi, Alat & Protokol |
| :--- | :--- |
| **Web & Frontend Systems** | Next.js 16 (App Router / RSC), React 19, Astro 5, TypeScript, JavaScript (ES6+), Tailwind CSS v4, Alpine.js, HTML5, CSS3, Vite |
| **Backend & Core Architecture** | Laravel 12 & 10, PHP 8.2+, Node.js, Express.js, Arsitektur RESTful API, Server-Side Rendering (SSR) |
| **Databases & Embedded Kernels** | SQLite 3 (Mode WAL), PostgreSQL 17 (Supabase), MySQL, Row-Level Security (RLS), Triggers, Stored Procedures Atomik |
| **Game Server & Modding** | Java 21, PaperMC API 1.21, Unity (Universal Render Pipeline), Pemrograman C#, Blender (3D Modeling & Environment) |
| **Cinematography & Visual Production** | Pengoperasian Kamera Manual, Penataan Lensa & Fokus, Kontinuitas Visual (*Continuity*), Tata Cahaya Sinematik, Camera Rigging |
| **Post-Production & Creative Tools** | Adobe Premiere Pro, Adobe After Effects, Adobe Photoshop, Adobe Illustrator, Adobe Audition, Adobe Media Encoder |
| **DevOps, Telemetry & Security** | Laravel Reverb (WebSockets), Linux (Ubuntu Server, Nginx), Git & GitHub Workflow, Postman, Vercel, Mitigasi OWASP Top 10 |
| **IT Ops & Infrastructure** | Diagnostik Perangkat Keras, Konfigurasi Jaringan LAN/WLAN, Mesin Asesmen CBT, Sistem Anti-Kecurangan Peramban |

---

### Professional Experience & Mentorship

#### **Founder & Lead Developer**
**Naverse Group (Naverse Teknologi Utama) | Apr 2026 : Present**
* Merancang dan memelihara infrastruktur terpadu untuk Naverse Academy, Naverse Technology, dan Naverse Studio.
* Menyusun kurikulum terstruktur (5 Modul Emas, 16 bab, 100 bank soal terstandarisasi) untuk literasi komputasi berbasis konsep.
* Mengimplementasikan orkestrasi kecerdasan buatan berbasis Groq dan rekonsiliasi pembayaran atomik Mayar API v2.

#### **Freelance Full-Stack Developer**
**Self-Employed | Feb 2024 : Present**
* Mengembangkan aplikasi web kustom, sistem basis data, dan modul automasi untuk klien independen, lembaga pendidikan, dan unit usaha.
* Mengintegrasikan antarmuka gerbang pembayaran, menyelesaikan kendala performa basis data, dan memperkuat batasan otorisasi sistem.
* Alat inti: Next.js, React, TypeScript, Laravel, PostgreSQL, MySQL, Tailwind CSS, REST APIs.

#### **IT & Technical Trainer**
**Freelance Mentorship | Aug 2025 : Mar 2026**
* Melaksanakan pelatihan privat terstruktur bagi 20+ peserta dengan fokus pada logika pemrograman dasar, algoritma komputasi, dan JavaScript.
* Membimbing peserta dalam instalasi server Linux Ubuntu mandiri, konfigurasi reverse proxy Nginx, dan prosedur peluncuran aplikasi ke server produksi.
* Mengajarkan prinsip komputasi fundamental mencakup hierarki memori kerja, aliran I/O standar, dan alur perulangan kejadian (*event loop*).

#### **Alumni Guest Speaker: Cyber Security Fundamentals**
**SMK Negeri 65 Jakarta | 2025**
* Diundang kembali ke SMKN 65 Jakarta sebagai narasumber alumni untuk memberikan pelatihan keamanan siber intensif kepada anggota ekstrakurikuler IT.
* Memberikan materi dan studi kasus mengenai prinsip pertahanan siber dasar, vektor serangan umum, sanitasi input, dan praktik pemrograman defensif.

#### **Data Support & Front-End Intern**
**PT Traspac Makmur Sejahtera | Sep 2024 : Feb 2025**
* Memvalidasi, memproses, dan menyusun data operasional menjadi laporan berkala untuk kebutuhan evaluasi manajemen.
* Mengembangkan antarmuka front-end internal guna meningkatkan visualisasi data operasional dan efisiensi pelaporan.
* Memastikan integritas data pada alur pencatatan log sistem dan mengotomatiskan rutinitas pengolahan lembar kerja data.

---

### Verified Credentials & Honors

* 📜 **BNSP Certified: Junior Software Developer**
  * *Badan Penerbit:* Badan Nasional Sertifikasi Profesi (LSP Informatika), Republik Indonesia
  * *Nomor Kredensial:* `62010 2512 0 0001043 2025` *(Diterbitkan Sep 2025, Berlaku hingga Sep 2028)*
  * *Validasi:* Menegaskan kompetensi nasional dalam rekayasa perangkat lunak, perancangan algoritma, pengodean terstruktur, dan pengelolaan basis data relasional.

* 🥉 **Bronze Medalist: Indonesian Youth Coding Olympiad**
  * *Penyelenggara:* Youth Coding Club *(Jul 2023)*
  * *Fokus:* Penyelesaian masalah algoritmik tingkat nasional, logika komputasi terstruktur, dan pemrograman kompetitif.

* 💼 **Data Support Internship Distinction**
  * *Penyelenggara:* PT Traspac Makmur Sejahtera *(Feb 2025)*
  * *Validasi:* Penghargaan atas keandalan analisis data operasional, penyusunan laporan internal, dan pengembangan dasbor front-end.

* 🎓 **Ijazah Sekolah Menengah Kejuruan: Rekayasa Perangkat Lunak**
  * *Institusi:* SMK Negeri 65 Jakarta *(Lulus 2025, Nilai Akhir: 87.5)*
  * *Kepemimpinan:* Ketua Coding Club (2024), Sekretaris Umum & Hubungan Masyarakat OSIS (2 periode jabatan).

---

### Open-Source & Community Utilities

* 🐍 **Snake Game (Interactive Exhibition Web Game):** Permainan interaktif berbasis web yang dibangun untuk demonstrasi stan pameran expo teknologi sekolah, menampilkan pengelolaan state antarmuka dan penanganan event input keyboard secara native.
* 🎁 **Giftly (Discord Giveaway Bot):** Bot utilitas ringan yang memanfaatkan API Discord untuk mengotomatiskan siklus undian dan penentuan pemenang melalui perintah berbasis kejadian (*event-driven commands*).

---

<div align="center">

### Contact & Collaboration

Terbuka untuk peluang rekayasa perangkat lunak, kontrak pengembangan sistem enterprise, konsultasi arsitektur komputasi, serta kolaborasi produksi multimedia.

<p>
  <a href="mailto:azhif.firdaus25@gmail.com">
    <img src="https://img.shields.io/badge/Email-azhif.firdaus25@gmail.com-d97706?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://anf-portfolio.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-anf--portfolio.vercel.app-0969da?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/athaillahnazhif/">
    <img src="https://img.shields.io/badge/LinkedIn-athaillahnazhif-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

<p>
  <i>Jakarta, Indonesia • © 2026 Athaillah Nazhif Firdaus. All rights reserved.</i>
</p>

</div>
