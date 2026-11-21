# Savers

Savers adalah rancangan aplikasi Android untuk membantu pengguna merencanakan target tabungan, mencatat transaksi, dan melihat ringkasan finansial.

Repository ini digunakan untuk Project Akhir mata kuliah Pengembangan Aplikasi Mobile 2026. Repository berisi informasi proyek dan progres pengerjaan. Dokumen SRS utama disusun di Google Docs.

## Dokumen SRS

[SRS Savers — Google Docs](https://docs.google.com/document/d/1XT27gxinHO_Ovg0fflHlBtPJ834ELYBstu-APiTE3tU/edit?usp=sharing)

SRS harus mengikuti template yang diberikan untuk mata kuliah. Cakupan dokumen mencakup kebutuhan dan fitur sistem, use case di Bab 2, flowchart dan activity diagram untuk setiap fitur di Bab 3, serta ERD dan Relasi Antar Tabel (RAT) di Bab 6. Kesesuaian isi dokumen dengan template akan ditinjau sebelum SRS ditetapkan.

## Ringkasan proyek

Savers dirancang untuk membantu pengguna membuat target tabungan dengan nominal dan tenggat, mencatat setoran serta transaksi umum, mengatur rencana setoran berkala, dan melihat ringkasan keuangan. Aplikasi juga direncanakan menyediakan laporan yang dapat diekspor ke PDF atau CSV.

## Teknologi dan batasan yang direncanakan

- Android: Kotlin, Jetpack Compose Material 3, Jetpack Navigation Compose, dan MVVM.
- State UI dikelola melalui ViewModel menggunakan StateFlow.
- Backend: REST API JSON dengan Node.js/Express.
- Database: PostgreSQL cloud.
- Autentikasi: JWT access token dan refresh token.
- Penyimpanan lokal untuk file/cache; Room, SQLite, XML layout, dan View tradisional tidak digunakan.

## Status

- [x] Repository publik dibuat.
- [x] README proyek disusun.
- [ ] SRS disusun dan ditinjau sesuai template mata kuliah.
- [ ] Kebutuhan TBD dan diagram SRS dilengkapi serta diperiksa.
- [ ] UI/UX dan alur navigasi dirancang.
- [ ] Aplikasi Android dan backend diimplementasikan.
- [ ] Fitur, keamanan, integrasi API, serta penanganan kondisi gagal diverifikasi.

Aplikasi Android dan backend belum diimplementasikan. Checklist ini akan diperbarui sesuai pekerjaan yang benar-benar selesai.

## Progres

| Tanggal | Progres |
| --- | --- |
| 2026-11-20 | Repository dibuat. |
| 2026-11-21 | Repository dikembalikan ke keadaan awal untuk memulai ulang dokumentasi proyek; README diperbarui untuk merujuk SRS di Google Docs. |

Pedoman proyek meminta pembaruan progres sekurang-kurangnya sekali setiap minggu dan minimal 30 commit nyata. Commit akan dibuat bertahap untuk mencatat perubahan yang benar-benar dikerjakan.

## Catatan

Nama repository `0216_Savers` mengikuti format pedoman dengan asumsi `0216` adalah empat digit terakhir NIM. Pastikan asumsi ini benar sebelum pengumpulan.
