# Savers

**Savers** adalah rancangan aplikasi Android untuk membantu pengguna merencanakan target tabungan, mencatat transaksi, dan melihat ringkasan finansial.

Repository ini dibuat untuk Project Akhir Pengembangan Aplikasi Mobile 2026. Nama repo mengikuti format pedoman dengan asumsi `0216` adalah empat digit terakhir NIM.

## Status proyek

- [x] Repository publik dibuat.
- [x] Draf awal SRS disusun di `docs/SRS.md` berdasarkan template SRS dan pedoman PAM 2026.
- [ ] Tinjau dan lengkapi metadata SRS yang masih bertanda TBD.
- [ ] Rancang UI/UX dan alur navigasi.
- [ ] Implementasikan aplikasi Android dengan Kotlin, Jetpack Compose Material 3, Navigation Compose, dan MVVM.
- [ ] Implementasikan REST API Node.js/Express dan PostgreSQL cloud.
- [ ] Verifikasi autentikasi JWT, authorization, CRUDS, ekspor lokal, serta penanganan error.

Status ini mencatat dokumentasi yang telah dibuat; aplikasi Android dan backend **belum diimplementasikan**.

## Teknologi dan batasan yang direncanakan

- Android: Kotlin, Jetpack Compose Material 3, Jetpack Navigation Compose, MVVM, dan StateFlow.
- Backend: REST API JSON dengan Node.js/Express dan PostgreSQL cloud.
- Autentikasi: email/kata sandi, JWT access token dan refresh token.
- Penyimpanan lokal: cache baca terenkripsi dan ekspor laporan PDF/CSV; tidak menggunakan Room atau SQLite.
- UI hanya menggunakan Compose; tidak menggunakan XML layout atau View tradisional.

## Progres

| Tanggal | Progres |
| --- | --- |
| 2026-11-20 | Repository dibuat; draf SRS v0.1 dan pemetaan terhadap pedoman PAM ditambahkan. |

Proyek dijaga dengan commit bertahap dan pembaruan progres sekurang-kurangnya satu kali setiap minggu. Jumlah commit akan mencerminkan pekerjaan nyata, dengan target minimal 30 commit sesuai pedoman.

## Dokumen

- [Software Requirements Specification](docs/SRS.md)
- [Pedoman Project Akhir PAM 2026](sources/PEDOMAN%20PROJECT%20AKHIR%20PAM%202026_.pdf) (referensi lokal; belum disalin ke repository)
