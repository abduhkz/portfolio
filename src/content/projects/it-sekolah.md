---
title: IT dan Sistem Administrasi Sekolah
summary: Server lokal, alat otomasi, dan pengolahan data untuk kebutuhan administrasi sekolah.
tags: [Server Lokal, Dapodik, e-Rapor, JavaScript, DOCX]
order: 3
draft: true
---
## Masalah
Pekerjaan administrasi sekolah banyak yang berulang dan dikerjakan manual: merekap absensi dari mesin sidik jari, mengetik surat dinas dengan format yang berbeda-beda, dan membersihkan data siswa serta alumni. Aplikasi seperti Dapodik dan e-Rapor juga bergantung pada satu komputer biasa.

## Yang saya kerjakan
- Membangun "VPS lokal" dari server sekolah (RAM 16 GB, Xeon E3-1225 v5) untuk hosting Dapodik dan e-Rapor.
- Membuat alat HTML satu file yang berjalan di browser untuk mengubah file DAT mesin ZKTeco menjadi rekap kehadiran pegawai, tanpa mengirim data ke server mana pun.
- Membuat template surat dinas .docx sesuai kaidah tata naskah dinas.
- Membersihkan dan menstandarkan data rekap siswa serta data penerimaan alumni di perguruan tinggi.

## Hasil
- Rekap absensi bulanan turun dari **sekitar 1 hari kerja menjadi beberapa menit** *(contoh)*.
- Dapodik dan e-Rapor berjalan di server khusus yang bisa dicadangkan dan dipulihkan *(contoh)*.
- Format surat dinas seragam dan lebih cepat dibuat *(contoh)*.

_Tempat demo: alat rekap ZKTeco dengan data contoh, bukan data pegawai asli._
