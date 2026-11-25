# Savers

Savers adalah rancangan aplikasi Android untuk membantu pengguna merencanakan target tabungan, mencatat transaksi, dan melihat ringkasan finansial.

Repository ini digunakan untuk Project Akhir mata kuliah Pengembangan Aplikasi Mobile 2026. Repository berisi informasi proyek dan progres pengerjaan. Dokumen SRS utama disusun di Google Docs.

## Dokumen SRS

[SRS Savers — Google Docs](https://docs.google.com/document/d/1aZGEV3Hqn4YbFgsdjfLHs4z3O_-ZLmrP/edit)

SRS harus mengikuti template yang diberikan untuk mata kuliah. Cakupan dokumen mencakup kebutuhan dan fitur sistem, use case di Bab 2, flowchart dan activity diagram untuk setiap fitur di Bab 3, serta ERD dan Relasi Antar Tabel (RAT) di Bab 6. Kesesuaian isi dokumen dengan template akan ditinjau sebelum SRS ditetapkan.

## Ringkasan proyek

Savers dirancang untuk membantu pengguna membuat target tabungan dengan nominal dan tenggat, mencatat setoran serta transaksi umum, mengatur rencana setoran berkala (`PRO`), mengelola anggaran bulanan (`PRO`), dan melihat ringkasan keuangan. Aplikasi juga menyediakan ekspor serta pembacaan kembali laporan PDF/CSV secara lokal, serta pembedaan hak akses berbasis peran (`STANDARD` dan `PRO`) termasuk simulasi perubahan paket di halaman Profil.

## Teknologi dan batasan yang direncanakan

- Android: Kotlin, Jetpack Compose Material 3, Jetpack Navigation Compose, dan MVVM.
- State UI dikelola melalui ViewModel menggunakan StateFlow.
- Backend: REST API JSON dengan Node.js/Express.
- Database: PostgreSQL cloud (6 entitas utama berelasi dengan field dinamis `JSONB`).
- Autentikasi & Otorisasi: JWT access token, refresh token, serta RBAC (`STANDARD` & `PRO`).
- Penyimpanan lokal untuk file laporan PDF/CSV (simpan & baca) dan cache offline terenkripsi; Room, SQLite, XML layout, dan View tradisional tidak digunakan.

## Status

- [x] Repository publik dibuat.
- [x] README proyek disusun.
- [x] SRS v0.2 disusun dan ditinjau sesuai template mata kuliah.
- [x] Kebutuhan dan 19 diagram SRS (Use Case, Flowchart, Activity Diagram, ERD, dan RAT) dilengkapi.
- [ ] UI/UX dan alur navigasi dirancang.
- [ ] Aplikasi Android dan backend diimplementasikan.
- [ ] Fitur, keamanan, integrasi API, serta penanganan kondisi gagal diverifikasi.

Aplikasi Android dan backend belum diimplementasikan. Checklist ini akan diperbarui sesuai pekerjaan yang benar-benar selesai.

## Progres

| Tanggal | Minggu | Progres |
| --- | --- | --- |
| 2026-11-20 | Week 1 | Repository dibuat. |
| 2026-11-21 | Week 1 | Repository dikembalikan ke keadaan awal untuk memulai ulang dokumentasi proyek; README diperbarui untuk merujuk SRS di Google Docs. |
| 2026-11-25 | Week 2 | Finalisasi SRS v0.2 (role `STANDARD` & `PRO`, 6 entitas `JSONB`, 5 fitur CRUDS penuh, simpan & baca PDF/CSV lokal) beserta 19 diagram UML, Flowchart, Activity, ERD, dan RAT. |

Pedoman proyek meminta pembaruan progres sekurang-kurangnya sekali setiap minggu dan minimal 30 commit nyata. Commit akan dibuat bertahap untuk mencatat perubahan yang benar-benar dikerjakan.

## Catatan

Nama repository `0216_Savers` mengikuti format pedoman dengan asumsi `0216` adalah empat digit terakhir NIM. Pastikan asumsi ini benar sebelum pengumpulan.
