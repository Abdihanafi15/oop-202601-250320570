# Catatan Minggu 01: Paradigma Pemrograman dan Setup

## Yang saya kerjakan
Saya mengisi tiga cara untuk membuat sapaan Aset-Pinjam: prosedural, berorientasi objek, dan fungsional. Ketiganya menerima nama dan NIM dengan cara berbeda, tetapi menghasilkan teks yang sama. Data nama dan NIM saya isi di `mahasiswa.properties`.

## Keputusan desain
Saya memakai kalimat `Hello Aset-Pinjam, saya [nama] ([NIM])` di ketiga versi agar perbedaan struktur pendekatan mudah dibandingkan. Pada versi OOP, nama dan NIM disimpan sebagai field `private final`; pada versi fungsional, lambda menangkap NIM dan menerima nama.

## Kendala
Tantangannya adalah menjaga keluaran ketiga pendekatan tetap identik meskipun bentuk kodenya berbeda. Saya menggunakan susunan teks dan tanda baca yang sama pada ketiganya.

## Penggunaan AI
- Alat yang dipakai: OpenAI Codex
- Bagian yang dibantu AI: implementasi `HelloProsedural.sapa`, field, konstruktor, dan `sapa` pada `HelloOOP`, lambda `HelloFungsional.pembuatSapaan`, serta penyusunan catatan ini.
- Prompt utama: Kerjakan minggu 01 berdasarkan panduan dan tes di repository.
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Belum ada perubahan atau penolakan; implementasi mengikuti aturan tugas dan menggunakan kalimat sapaan yang sama di semua pendekatan.
- Satu hal yang saya pahami lebih baik sekarang: Lambda dapat dikembalikan sebagai nilai fungsi dan dapat memakai nilai NIM yang ditangkap saat fungsi itu dibuat.
