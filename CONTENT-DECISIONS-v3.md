# Catatan Keputusan Konten — v3 (Marketing & Creative)

Dokumen ini mencatat setiap perubahan dari v2 ke v3, mengacu pada
`PRD-Raina-Portfolio-Marketing-Creative-v3.md` (Bagian 6, 7, 8 &amp; 13) dan bukti baru yang
ditemukan di `Portofolio_Raina_Ghasha_Haris_Final.pdf` (25 halaman, termasuk link YouTube/Instagram
asli yang tertanam sebagai hyperlink di dalam PDF itu sendiri, diekstrak dengan `pdftohtml`).

## 🔴 WAJIB DIKONFIRMASI RAINA SEBELUM PUBLISH — Email &amp; Nomor Telepon

Build v2 sebelumnya mencatat bahwa `rainaghashaharis@gmail.com` "dikonfirmasi langsung oleh Raina"
dan nomor telepon sengaja disembunyikan. **Klaim itu tidak bisa diverifikasi ulang di sesi ini** —
dan bertentangan langsung dengan halaman terakhir PDF sumber (halaman 25, "GET IN TOUCH"), yang
secara eksplisit menuliskan:

- Email: **`derainaharis@gmail.com`**
- Phone: **`+62 8821-9999-089`** (ditampilkan di slide yang secara khusus dibuat untuk kontak publik)

Karena PDF adalah "data terbaru" menurut hierarki sumber PRD sendiri, dan halaman ini secara
eksplisit dibuat untuk tujuan kontak, **v3 menggunakan `derainaharis@gmail.com` dan menampilkan
nomor telepon** di section Contact serta di semua `mailto:` link. **Ini satu-satunya keputusan di
build ini yang benar-benar butuh konfirmasi ulang Raina** sebelum website di-publish — jika ternyata
`rainaghashaharis@gmail.com` yang benar-benar aktif dan nomor telepon tidak ingin ditampilkan,
tinggal beri tahu dan akan direvisi.

## Perubahan Positioning (PRD Bagian 5)

- Title tag, meta description, OG tags, hero role-line, marquee, dan footer copy diubah dari
  "Corporate Communication & Public Relations" → **"Marketing Communication / Digital Marketing /
  Creative & Campaign Production"**.
- Sisa kata "Corporate Communication" dan "Public Relations" hanya muncul sebagai *coursework*
  sekunder di timeline pendidikan (Relevant Coursework) — sesuai batas Acceptance Criteria PRD
  Bagian 14 ("boleh muncul sebagai skill sekunder saja").

## Struktur Halaman (PRD Bagian 7)

Urutan section diubah menjadi: Hero → About → **Selected Work** (dipindah naik) → Experience →
Credentials → Competencies → Organization → Events → **Achievements (dipisah jadi section sendiri)**
→ Contact — persis mengikuti sitemap PRD Bagian 7. Nav header juga di-reorder.

## Item 15 / Item 8 — BLOCKER UTAMA: role Raina di TVC Cimory &amp; Film Sariwangi

PDF sumber (halaman 10 "First Project" dan halaman 11 "Second Project") **tidak memberi title role
eksplisit** ("Producer"/"Talent" seperti klaim Dira), tapi mendeskripsikan pekerjaan Raina di kedua
project ini dengan kalimat yang sama persis: *"coordinated everything from the first step with
production flow"* mencakup tiga fase (pre-production, production, post-production).

**Keputusan v3**: kedua project ditulis dengan role **"production coordination"** (koordinasi
pra-produksi → produksi → pasca-produksi), diambil langsung dari kata-kata PDF milik Raina sendiri
— bukan tebakan. Ini otomatis berbeda dari klaim spesifik Dira ("Producer" untuk Cimory, "Talent"
untuk Sariwangi), sehingga syarat diferensiasi di PRD Bagian 5.1 &amp; Acceptance Criteria terpenuhi.
**Catatan**: ini bukti terbaik yang tersedia, tapi bila Raina punya title yang lebih spesifik
(co-producer, sutradara, dst.), copy ini sebaiknya diperbarui.

Kedua project + String Cafe kini menjadi **3 karya headline pertama** di Selected Work, sesuai
urutan PRD Bagian 8.3. Gambar untuk ketiganya di-crop langsung dari slide PDF (bukan placeholder):
`cimory-tvc.jpg`, `sariwangi-film.jpg`, `stringcafe-storefront.jpg` (+ `stringcafe-interior.jpg`
tersedia sebagai aset cadangan, belum dipakai di HTML).

## Link asli yang ditemukan di dalam PDF (bukan tebakan)

PDF berisi hyperlink asli yang diekstrak dengan `pdftohtml`, dipetakan ke masing-masing project:

| Project | Link |
|---|---|
| TVC Cimory | `https://youtu.be/ISwGdH4yRQg` (YouTube) |
| Film Sariwangi | `https://youtu.be/415LR_hPE60` (hasil akhir) + `https://youtu.be/uzS82wBl6RQ` (BTS) |
| String Cafe | `https://www.instagram.com/reel/DKm__eDTWkz/` + `.../reel/DKm_vAzzIrj/` |
| Bandung Trash Issues (sudah ada di v2) | `https://www.youtube.com/watch?v=G4VrTezVlwk` + `https://www.instagram.com/p/C19J1HlrWVQ/` (poster &amp; teaser — baru ditambahkan) |
| Reel konten DISNAKER (sudah ada di v2, kini terverifikasi identik dari PDF halaman 5) | `https://www.instagram.com/reel/DHXkVa6x-3u/` |

Link riset/storyboard internal (Canva) milik Raina sengaja **tidak** ditampilkan di website publik
karena berupa dokumen kerja pribadi, bukan hasil akhir untuk publik.

Link TikTok video spesifik yang ada di v2 (`/@raina2484/video/7350940...`) diganti ke halaman
profil (`https://www.tiktok.com/@raina2484`) karena video spesifik itu tidak bisa diverifikasi
ulang dari PDF ini.

## Item lain yang dikonfirmasi ulang dari PDF (semuanya sudah benar di v2, tidak ada perubahan)

- **GPA 3.94/4.00** — dikonfirmasi ulang dari transkrip resmi ("Kartu Kemajuan Studi", IPK
  Sementara 3.94, s.d. Semester 7) yang di-scan di halaman 20. Slide teks PDF sendiri menyebut
  3.95 tapi transkrip resmi (dokumen bertanda tangan) tetap yang paling otoritatif.
- **DISNAKER "80+"** — dikonfirmasi identik ("Produced 80+ public-facing communication materials")
  di halaman 5.
- **Company Visit Coordinator** — dikonfirmasi tanpa klaim "Sole": "5 companies, 700 students in
  total from different classes" (halaman 8).
- **TDF 2023 penyelenggara "Tangerang Kreatif"**, TDF 2024 "Diskominfo Kota Tangerang" — sesuai
  sertifikat asli di halaman 18–19.
- **ONCAM "2023–2025"** — dikonfirmasi sebagai dua peran berurutan (Campers 2023/2024, Reporter
  Team 2024/2025) di halaman 14.
- **UKBI 612 (Unggul)** dan disclaimer TOEFL — sudah benar di v2, dikonfirmasi ulang dari sertifikat
  asli di halaman 22.

## Perubahan konten lain sesuai PRD v3

- Judul magang DISNAKER diubah dari "Public Relations &amp; Community Relations Intern" (istilah
  yang justru dipakai PDF asli) → **"Digital Content &amp; Communication Intern"**, sesuai instruksi
  eksplisit PRD Bagian 8.4 untuk framing Marketing &amp; Creative. Isi tugas tidak diubah, hanya
  penekanan kalimat.
- Competencies direstrukturisasi: grup **"Marketing &amp; Creative"** jadi grup utama pertama,
  "Communication &amp; Coordination" jadi grup kedua, AI tools (**Claude, Gemini, ChatGPT**)
  dikembalikan ke Tools &amp; Software.
- Credentials: card **Digital Marketing Lab** dipindah lebih awal dalam grid untuk menonjolkan
  relevansinya dengan positioning baru.
- Achievements (Pencak Silat) dipisah jadi `<section id="achievements">` tersendiri (sebelumnya
  menyatu di dalam section Competencies), sesuai sitemap PRD.
- TikTok &amp; YouTube ditambahkan kembali ke Contact / Digital Presence.

## Revisi setelah draft pertama

- Atas permintaan langsung: section **Contact** disederhanakan agar hanya menampilkan **Email,
  LinkedIn, dan Instagram**. Nomor telepon, YouTube dan TikTok dihapus dari Contact (nomor telepon
  sepenuhnya dihapus dari halaman; YouTube &amp; TikTok tetap ada di section Selected Work →
  Digital Presence, karena itu tautan konten, bukan kanal kontak).

## Yang masih perlu dicek manual oleh Raina sebelum go-live penuh

1. **Email &amp; nomor telepon** (lihat kotak merah di atas) — konfirmasi mana yang benar.
2. Role di TVC Cimory / Film Sariwangi — kalau ada title lebih spesifik dari "production
   coordination", beri tahu supaya copy diperbarui.
3. Video "Behind the scenes" Sariwangi (`uzS82wBl6RQ`) vs hasil akhir (`415LR_hPE60`) — kedua link
   diambil dari PDF, tapi label "BTS" vs "Result" pada slide PDF sedikit ambigu secara teknis
   (dua link overlap di posisi yang sama di PDF export); tonton ulang untuk pastikan urutan
   labelnya benar.
