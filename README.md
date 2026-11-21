
<h1 align="center">
  🖥️ LabAssess (Laboratory Assessment System)
<hr/>
<p align="center">
  <img src="https://img.shields.io/badge/REACT.JS-B9DDF0?style=flat&logo=react&logoColor=34495E" />
  <img src="https://img.shields.io/badge/PYTHON-C9D9F2?style=flat&logo=python&logoColor=34415B" />
  <img src="https://img.shields.io/badge/FASTAPI-BCE5D5?style=flat&logo=fastapi&logoColor=285B4A" />
  <img src="https://img.shields.io/badge/MARIADB-D8C8E9?style=flat&logo=mariadb&logoColor=514365" />
  <img src="https://img.shields.io/badge/VITE-F5D7A8?style=flat&logo=vite&logoColor=70552D" />
</p>

<p align="center">
  Aplikasi Sistem Informasi Penilaian Laboratorium untuk mengelola
  kegiatan praktikum, modul pembelajaran, kuis, dan evaluasi mahasiswa
  secara terpusat.
</p>

<hr/>

## ✨ Fitur Unggulan

LabAssess menyediakan fitur pengelolaan laboratorium berdasarkan tiga jenis pengguna dengan hak akses yang berbeda.

### 👨‍💼 Administrator
- **Manajemen Akun:** Mengelola akun mahasiswa dan asisten laboratorium.
- **Manajemen Mahasiswa:** Mengelola data mahasiswa berdasarkan NIM dan program studi.
- **Pengelolaan Asisten:** Membuat dan mengelola akun asisten laboratorium.
- **Pembagian Mahasiswa:** Mengatur penempatan mahasiswa ke asisten dan mata kuliah.

### 👩‍🏫 Asisten Laboratorium
- **Manajemen Modul:** Mengelola materi dan modul praktikum.
- **Manajemen Soal:** Membuat dan mengelola bank soal.
- **Manajemen Kuis:** Membuat, mengatur, dan mempublikasikan kuis.
- **Penilaian:** Mengelola hasil evaluasi mahasiswa.

### 🎓 Mahasiswa
- **Registrasi dan Login:** Mengakses aplikasi menggunakan akun mahasiswa.
- **Dashboard Mahasiswa:** Melihat informasi akademik dan aktivitas praktikum.
- **Materi Praktikum:** Mengakses modul pembelajaran.
- **Kuis Online:** Mengerjakan kuis yang tersedia.
- **Hasil Penilaian:** Melihat hasil evaluasi.

---

## 📸 Tampilan Aplikasi

Berikut merupakan dokumentasi antarmuka LabAssess berdasarkan masing-masing hak akses pengguna.

### 🔐 Halaman Login

<img width="950" height="439" alt="image" src="https://github.com/user-attachments/assets/99517357-beb0-4d27-ab03-c19e3f009c09" />

<img width="940" height="437" alt="image" src="https://github.com/user-attachments/assets/d8ea1bdf-d085-44d0-bfb4-8cca82e5321a" />


### 👨‍💼 Dashboard Administrator
1.Menu Overview
<img width="566" height="404" alt="image" src="https://github.com/user-attachments/assets/30eb8ada-ed9b-4928-bad2-a463ac9ce15c" />

2.Menu Pengguna
<img width="560" height="414" alt="image" src="https://github.com/user-attachments/assets/b6819c02-beb4-4db1-85b9-c24a47ab85b1" />

3.Menu Mata Kuliah
<img width="557" height="323" alt="image" src="https://github.com/user-attachments/assets/5dace82e-0872-4b1c-8fff-33302c78f92e" />

4.Menu Penempatan
<img width="568" height="322" alt="image" src="https://github.com/user-attachments/assets/a24ee042-38fa-49f1-9da3-aa2039d636ee" />

### 👩‍🏫 Dashboard Asisten Laboratorium
1.Menu Overview
<img width="884" height="436" alt="image" src="https://github.com/user-attachments/assets/fb35148e-b261-4f89-9b02-00fea98ec2e6" />

2.Menu Kelas Saya
<img width="887" height="325" alt="image" src="https://github.com/user-attachments/assets/8a7ec75c-d24d-470f-9fc7-106923ae7de7" />

3.Menu Pre Test & Post Test
<img width="884" height="278" alt="image" src="https://github.com/user-attachments/assets/eb3149d2-de5b-4cbc-9d97-3afcbcac960c" />

4.Menu Rekap Nilai
<img width="887" height="395" alt="image" src="https://github.com/user-attachments/assets/e97783a7-79bf-49be-82d6-0b3389eef9e5" />

### 🎓 Dashboard Mahasiswa
1.Menu Overview
<img width="871" height="410" alt="image" src="https://github.com/user-attachments/assets/06d95171-73cc-4cf7-af12-5b534fc0d7c2" />

2.Menu Kelas Saya
<img width="899" height="281" alt="image" src="https://github.com/user-attachments/assets/93c99783-6303-448b-9d2c-855225880b13" />

3.Menu Riwayat Nilai
<img width="885" height="369" alt="image" src="https://github.com/user-attachments/assets/36ec2b11-a0d6-439e-8c57-466b77573e5f" />


## 🛠️ Teknologi dan Tools

| Teknologi | Kegunaan |
|---|---|
| React.js | Pengembangan antarmuka pengguna |
| Vite | Build dan development frontend |
| Python | Bahasa pemrograman backend |
| FastAPI | Pengembangan backend dan REST API |
| SQLAlchemy | ORM untuk pengelolaan database |
| MariaDB / MySQL | Pengelolaan database relasional |
| Lucide React | Ikon antarmuka |

## 🏗️ Arsitektur Sistem

LabAssess menggunakan arsitektur client-server yang mengintegrasikan tiga komponen utama:

```text
        USER
          |
          v
    REACT.JS (Frontend)
          |
          v
      REST API
          |
          v
    FASTAPI (Backend)
          |
          v
      SQLALCHEMY
          |
          v
    MARIADB / MYSQL
```

Setiap komponen memiliki tanggung jawab tersendiri dalam mendukung proses pengelolaan data dan aktivitas laboratorium.

---

## 📂 Struktur Proyek

```text
LabAssess/
│
├── backend/
│   ├── app/
│   ├── migrations/
│   └── storage/
│
├── frontend/
│   └── src/
│
├── docs/
│
├── .gitignore
└── README.md
```

## 🎯 Tujuan Pengembangan

LabAssess dikembangkan untuk mendukung digitalisasi pengelolaan kegiatan praktikum laboratorium, mempermudah proses administrasi, serta menyediakan sistem evaluasi mahasiswa yang terintegrasi.

---

<p align="center">
  <b>LabAssess — Laboratory Assessment System</b>
  <br/>
  Sistem Penilaian Laboratorium Berbasis Web
</p>
