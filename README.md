# BGeoDev API Testing

Repository ini digunakan untuk menyimpan collection API testing menggunakan Bruno.

## Tools

* Bruno
* Git
* GitHub

## Tujuan Repository

Repository ini dibuat untuk:

* Testing endpoint API
* Kolaborasi antar backend/frontend developer
* Menyimpan dokumentasi request API
* Mempermudah QA dan debugging
* Versioning collection API menggunakan Git

---

# Requirement

Sebelum menggunakan repository ini, pastikan sudah menginstall:

* Git
* Bruno

## Download Bruno

[https://www.usebruno.com/downloads](https://www.usebruno.com/downloads)

---

# Cara Menggunakan

## 1. Clone Repository

```bash
git clone https://github.com/cahyailhamketua/bgeodev_api_testing.git
```

## 2. Buka Collection di Bruno

1. Buka Bruno
2. Klik "Open Collection"
3. Pilih folder hasil clone repository

---

# Workflow Team

## Mengambil Update Terbaru

```bash
git pull origin main
```

## Menambahkan Endpoint Baru

```bash
git add .
git commit -m "add new endpoint"
git push origin main
```

---


## Gunakan Naming yang Konsisten

Contoh:

* get_users
* create_schedule
* update_project
* delete_team

---

# Best Practice

* Pisahkan endpoint berdasarkan module
* Gunakan folder sesuai feature
* Gunakan environment berbeda untuk dev/staging/production
* Selalu pull sebelum push

---

# Contribution

1. Pull latest changes
2. Tambahkan endpoint baru
3. Commit dengan message yang jelas
4. Push ke repository

---

# Notes

Repository ini menggunakan Bruno karena:

* Local-first
* Git friendly
* Gratis untuk collaboration
* Lightweight
* Mudah digunakan untuk team development
