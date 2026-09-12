# Audit Modul 2 - Semantic HTML & Form Peminjaman

## Catatan Sebelum Diperbaiki

| Temuan Masalah                                          | Lokasi File       | Kondisi           | Solusi                                                  |
| ------------------------------------------------------- | ----------------- | ----------------- | ------------------------------------------------------- |
| Daftar peralatan masih menggunakan list biasa (`ul/li`) | `peralatan.html`  | Struktur DOM lama | Mengganti pakai elemen semantik (`section` + `article`) |
| Halaman form peminjaman belum ada                       | `peminjaman.html` | File belum dibuat | Buat file baru dan susun form peminjaman                |

## Checklist Setelah Diperbaiki

- [x] Struktur landmark halaman udah rapi (`header`, `nav`, `main`, `footer`).
- [x] Urutan heading-nya jelas dan masuk akal (`h1` -> `h2` -> `h3`).
- [x] Katalog minimal ada 3 alat, lengkap pakai tag `figure` dan `figcaption`.
- [x] Kalo label diklik, cursor/fokus langsung masuk ke input-nya (atribut `for` dan `id` udah klop).
- [x] Semua field input penting udah dikasih atribut `name` buat pengiriman data.
- [x] Validasi HTML native jalan (submit kosong langsung ditahan sama browser).
- [x] Navigasi keyboard aman (pindah-pindah field pake tombol `Tab` urut, ga loncat-loncat).
- [x] Udah dicek lewat W3C Validator dan bebas dari error utama.
