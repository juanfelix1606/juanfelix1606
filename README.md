# Hai, saya Juan Felix 👋

Mahasiswa Informatika yang tertarik pada pengembangan **fullstack** dengan React, TypeScript, Node.js, dan PostgreSQL. Saya sedang mencari kesempatan magang atau posisi junior.

## Proyek utama

### [CampusHub](https://github.com/juanfelix1606/CampusHub)

Sistem informasi kampus yang menggabungkan LMS sederhana dan absensi berbasis QR, dengan tiga peran: admin, dosen, dan mahasiswa.

- Absensi QR dengan token berotasi 30 detik yang divalidasi di server; absensi ganda dicegah lewat transaksi, row lock, dan unique constraint.
- Otorisasi per peran di backend, dengan refresh token acak yang disimpan sebagai hash dan dirotasi.
- Pengujian unit, integration (PostgreSQL sungguhan), dan E2E Playwright yang berjalan otomatis lewat GitHub Actions.

Status: belum dideploy (tidak ada demo live). Screenshot dan dokumentasi ada di README repositori.

## Tech stack

- **Frontend:** React, TypeScript, Vite, Tailwind CSS
- **Backend:** Node.js, Express, Prisma
- **Database:** PostgreSQL
- **Testing dan CI:** Vitest, Supertest, Playwright, GitHub Actions

## Kontak

- [LinkedIn](https://www.linkedin.com/in/juan-felix-b4322841b/)
