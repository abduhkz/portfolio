---
title: Website SMAN 17 Makassar
summary: Mengelola dan mengoptimalkan website resmi sekolah berbasis WordPress agar cepat dan konsisten.
tags: [WordPress, Elementor, REST API, PageSpeed]
order: 1
draft: true
---
## Masalah
Website sekolah dibangun dengan Elementor dan banyak plugin, sehingga halaman beranda terasa lambat di ponsel, terutama saat memuat gambar utama. Tampilan beranda juga belum konsisten dengan identitas visual sekolah, dan widget berita belum menampilkan thumbnail artikel.

## Yang saya kerjakan
- Mengukur performa dengan PageSpeed Insights (mobile dan desktop), lalu menelusuri penyebab LCP yang tinggi.
- Mengganti bagian hero beranda dengan HTML/CSS kustom yang ringan, mengikuti brand system sekolah (biru, oranye, abu-abu tua, font Roboto).
- Membuat widget "Berita & Pengumuman" kustom yang mengambil data dari REST API WordPress.
- Mengurangi beban font eksternal dan merapikan plugin, serta mengamankan halaman login.

## Hasil
- Skor PageSpeed mobile naik dari **42 menjadi 78** *(contoh)*.
- LCP turun dari **5,8 detik menjadi 2,4 detik** *(contoh)*.
- Beranda tampil konsisten dengan identitas sekolah dan berita terbaru tampil otomatis *(contoh)*.

_Tempat screenshot: sebelum/sesudah PageSpeed dan tampilan beranda._
