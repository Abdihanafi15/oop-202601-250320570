# Catatan Minggu 01: Paradigma Pemrograman dan Setup

## Yang saya kerjakan
Saya mengisi ketiga cara untuk membuat sapaan Aset-Pinjam untuk prosedural, berorientasi objek dan fungsional.saya juga mengisi mahasiswa.propertis dengan NIM dan nama saya, sebelum megerjakan tugas saya menginstal Git, kemudain melakukan clone pada repo tugas serta mengunduh jdk 21. tapi untuk maven belum saya unduh di laptop saya, tetapi saya bisa menjalankan test melalui VS Code untuk minggu01 test dan hasilny hijau.

## Keputusan desain
Saya memakai kalimat Hello Aset-Pinjam, saya [nama] [NIM] di ketiga versi. untuk nama dan nim dibaca dari mahasiswa properties

## Kendala
- saya sempat mengubah kode dari ai yaitu urutan nama dulu baru NIM pada fungsional mengikuti pada proseduraL dan method OOP tapi untuk hasil berbeda dengan prosedural dan method OOP, kemudian kalimat "Halo" dan "Hello" yang berbeda di tiap filenya.
- untuk `scripts/uji.ps1` belum bisa dijalankan karena saya belum mengunduh maven 

## Penggunaan AI
- Alat yang dipakai: Claude dan Codex
- Bagian yang dibantu AI: 
menjelaskan maksud untuk tugas minggu-01 dengan scrennshoot tugas dan isi file, membrikan contoh kode, mencari tes yang gagal, dan mencari tau perbedaan dari ketiga file.
- Prompt utama: 
1. jelaskan apa yang dimaksud untuk tugas ini dan berikan kode yang perlu serta jelaskan alur kodenya
2. lalu menanyakan arti Minggu01Test,
  kenapa tes error setelah kode diubah.
3. kenapa urutan parameter fungsional
  berbeda dan jelaskan perbedaan dari ketiganya.
- Yang saya ubah atau tolak dari saran AI, dan alasannya: - Yang saya ubah atau tolak dari saran AI: kalimat sapaan awalnya dari AI
  ("Halo Aset-Pinjam, saya [nama] ([NIM])"). Saya ubah kata "Halo" menjadi
  "Hello" sendiri, lalu saya samakan di ketiga file supaya tes
  Saya juga mencoba mengubah urutan nama dulu baru NIM pada versi fungsional untuk memastikan hasilnya dan benar pada minggu01 test
- Satu hal yang saya pahami lebih baik sekarang: dari ketiga versi 
  - Prosedural: data dikirim lewat parameter      ke statis, jadi alurnya
    hanya urutan langkah dan tidak ada objek atau state yang disimpan.
  - OOP: data (nama dan NIM) disimpan sebagai field di dalam
  - Fungsional: lambda dapat dikembalikan sebagai nilai fungsi
  Saya juga belajar bahwa ketiganya bisa menghasilkan teks yang sama walaupun
  cara data masuknya berbeda, dan bahwa minggu01tes adalah acuan kode harus mengikuti
  tes, bukan sebaliknya.
