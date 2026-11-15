# SIGAP — Sistem Pengawasan RSUD M. Natsir

Sistem internal rumah sakit daerah untuk absensi pegawai, laporan kinerja harian, dan penilaian KPI lintas peran.

## Kegunaan

- Absensi pegawai dan Laporan Kinerja Harian (LKH) dengan validasi berjenjang.
- Penilaian kinerja dan KPI pegawai.
- Monitoring kehadiran dan apel.
- Aplikasi Android untuk pegawai lapangan.

## Tech stack

| Lapis | Teknologi |
|---|---|
| Backend | Laravel 11 (PHP 8.2), 41 model, 40 migrasi, 27 controller, 407 route API |
| Frontend | Vue 3, Pinia, Vite |
| Mobile | Ionic Vue + Capacitor (Android) |
| Layanan citra | FastAPI + YOLOv8 |
| Data | PostgreSQL 16, Redis 7 |
| Infrastruktur | Docker Compose |

## Alur singkat

1. Pegawai login sesuai peran, lalu mengisi absensi dan LKH.
2. Atasan memvalidasi LKH secara berjenjang.
3. Penilaian kinerja dihitung dari data absensi dan LKH.
4. Pimpinan memantau rekap lewat dashboard per peran.

## Ringkasan

| | |
|---|---|
| Mulai dikembangkan | Mei 2026 |
| Status | Aktif dipakai dan dikembangkan |

> Kode sumber tidak dipublikasikan. Repo ini hanya menjelaskan kegunaan, stack, dan alur kerja. Tidak ada data pengguna, data pasien, atau kredensial di sini.
