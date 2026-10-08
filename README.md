# Telkom University Company Profile - Praktikum

Project simulasi website Company Profile Telkom University yang dibuat untuk
mempelajari HTML, CSS, PHP Native, MySQL/MariaDB, serta Git dan GitHub.

> Catatan: Konten institusi pada website bersifat simulasi untuk kebutuhan
> pembelajaran dan praktikum.

## Struktur Project

```text
telkom-company-profile/
│
├── admin/
│   ├── add_news.php
│   └── save_news.php
├── assets/
│   └── css/
│       └── style.css
├── config/
│   └── database.php
├── database/
│   └── telkom_profile.sql
├── includes/
│   ├── header.php
│   └── footer.php
├── index.php
├── profile.php
├── programs.php
├── news.php
├── news_detail.php
├── contact.php
├── contact_process.php
├── README.md
└── .gitignore
```

## Fitur

- Beranda
- Profil
- Program Studi
- Berita dan Detail Berita
- Form Kontak
- Admin Lokal untuk menambahkan berita

## Teknologi

- HTML & CSS
- PHP Native
- MySQL/MariaDB
- Git & GitHub
- Laragon
- phpMyAdmin

## Database

Database yang digunakan:

```text
telkom_profile
```

Tabel utama:

```text
program_studi
berita
pesan
```

## Menjalankan Project

Project menggunakan Laragon.

1. Jalankan **Laragon → Start All**.
2. Letakkan project di:

```text
C:\laragon\www\telkom-company-profile
```

3. Buat database `telkom_profile` melalui phpMyAdmin.
4. Import file `database/telkom_profile.sql`.
5. Buka:

```text
http://localhost/telkom-company-profile/
```

## Riwayat Praktikum Git

Project dikembangkan secara bertahap menggunakan Git melalui beberapa
milestone.

```text
Project & Repository
        ↓
Layout, Header, Footer & CSS
        ↓
Database & Program Studi
        ↓
Berita & Detail Berita
        ↓
Form Kontak & Database
        ↓
Feature Branch & Merge
        ↓
Merge Conflict
        ↓
Kolaborasi Laptop A & B
        ↓
Recovery Perubahan
        ↓
Release & Tag v1.0.0
```

### Branch dan Merge

Feature branch yang digunakan:

```text
feature-campus-info
```

Branch kemudian digabungkan kembali ke `main`.

### Merge Conflict

Simulasi merge conflict dilakukan pada:

```text
includes/header.php
```

Conflict diselesaikan secara manual kemudian hasilnya di-commit dan di-push
kembali ke repository.

### Kolaborasi Laptop A & B

Simulasi dilakukan dengan melakukan clone repository ke folder kedua,
melakukan perubahan dan push dari folder tersebut, kemudian melakukan pull
pada folder pertama.

Pada proses ini juga dilakukan simulasi conflict pada `README.md` dan
penyelesaiannya.

### Recovery

Beberapa perintah Git yang dipraktikkan:

```bash
git restore
git restore --staged
git revert
```

## Release

Versi final project ditandai dengan tag:

```text
v1.0.0
```

Tag dibuat menggunakan:

```bash
git tag -a v1.0.0 -m "Rilis praktikum versi 1.0.0"
git push origin v1.0.0
```

## Riwayat Commit

Riwayat project dapat dilihat menggunakan:

```bash
git log --oneline --graph --decorate --all
```