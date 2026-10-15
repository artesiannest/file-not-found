# File Not Found — A Digital Mystery
Game puzzle naratif berbahasa Indonesia. Jelajahi laptop Alea, baca pesan, buka folder pribadi, pulihkan berkas lewat terminal fiktif, dan tentukan akhir cerita.

## Mainkan
Ekstrak ZIP lalu buka index.html di browser modern. Semua aset lokal, tanpa instalasi, database, API key, atau CDN. Durasi sekitar 5–10 menit. Tidak ada jumpscare.

## Upload dan publikasikan di GitHub
1. Buat repository **Public** bernama `file-not-found`.
2. Upload seluruh **isi folder** ini, bukan ZIP. Pastikan index.html ada di root repository bersama app.js, style.css, icon.svg, dan .nojekyll.
3. Commit changes.
4. Settings → Pages → Deploy from a branch → main → /(root) → Save.
5. Tunggu deployment selesai. URL ditampilkan di Pages, umumnya https://USERNAME.github.io/file-not-found/.
Jika branch berbeda, pilih branch tempat file diupload. Deployment dapat dilihat di Actions.

## Fitur
- Desktop virtual, Inbox, Files, Terminal, dan catatan bukti otomatis.
- Jendela dapat digeser dengan pointer di desktop. Navigasi satu klik/ketuk dan keyboard lewat tombol asli.
- Puzzle akrostik dan kode waktu, terminal dengan daftar perintah terbatas (tidak menjalankan shell).
- Tiga akhir cerita yang dapat dicoba tanpa menghapus bukti.
- Bulan, awan, bintang, waveform dekoratif, transisi jendela, dan suara interaksi opsional.
- Layout HP sampai 320px, tablet, desktop; target sentuh minimal 44px untuk kontrol utama. Reduced motion dihormati.
- Autosave lokal dan reset dengan konfirmasi. Jika penyimpanan browser dibatasi, progres bertahan selama sesi halaman terbuka.

## Struktur
index.html — struktur desktop; style.css — desain dan animasi; app.js — cerita, puzzle, state, drag, audio; icon.svg — favicon.

## Deskripsi portfolio
File Not Found adalah game misteri interaktif dengan desktop virtual yang mengajak pemain menelusuri jejak seseorang melalui email, berkas terkunci, dan terminal pemulihan. Dibangun menggunakan HTML, CSS, dan JavaScript dengan animasi, tampilan mobile responsive, progres lokal, dan tiga akhir cerita.
Kategori: Narrative Puzzle / Digital Mystery.

## Catatan
Seluruh karakter, alamat, tanggal, terminal, dan kejadian adalah fiksi. Tidak ada email yang dikirim, file perangkat yang dibaca, atau jaringan nyata yang diretas. Folder terkunci adalah mekanik puzzle; jawabannya ada di source dan bukan keamanan sungguhan. Progres tidak tersinkron antar perangkat. Tidak memakai AI/backend. Gunakan browser modern dengan dukungan dialog dan Pointer Events.
