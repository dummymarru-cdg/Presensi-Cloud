# ☁️ Sistem Presensi Online Berbasis Cloud Computing

## 📌 Deskripsi

Sistem Presensi Online Berbasis Cloud Computing merupakan aplikasi sederhana yang dibuat untuk mempermudah proses pencatatan kehadiran mahasiswa secara online. Sistem ini memanfaatkan layanan cloud computing sehingga presensi dapat dilakukan melalui internet dan data tersimpan secara otomatis pada cloud.

Proyek ini merupakan implementasi konsep **Software as a Service (SaaS)**, **Platform as a Service (PaaS)**, dan **Infrastructure as a Service (IaaS)** menggunakan platform gratis.

---

## 🛠️ Teknologi yang Digunakan

- HTML5
- CSS3
- GitHub
- Vercel (PaaS)
- Google Forms (SaaS)
- Google Sheets (Cloud Database)
- Oracle Cloud Free Tier (IaaS - Pengembangan)

---

# Cara Menggunakan Sistem

### 1. Buka Website

Akses website melalui browser menggunakan domain yang telah di-deploy di Vercel.

Contoh:

```
https://presensi-cloud-seven.vercel.app
```

---

### 2. Halaman Utama

Pada halaman utama tersedia:

- Judul Sistem Presensi
- Tombol **Isi Presensi**
- QR Code Presensi
<img src="Preview Web.png" width="250">

---

### 3. Melakukan Presensi

Mahasiswa dapat melakukan presensi dengan dua cara:

- Klik tombol **Isi Presensi**
- Scan QR Code menggunakan smartphone

Kedua cara tersebut akan mengarahkan pengguna menuju Google Forms.

---

### 4. Mengisi Form Presensi

Mahasiswa mengisi data yang diperlukan, antara lain:

- Nama
- NPM
- Kelas
- Status Kehadiran

Setelah semua data terisi, tekan tombol **Submit**.

---

### 5. Penyimpanan Data

Data yang dikirim akan otomatis tersimpan pada Google Sheets sebagai database cloud.

---

### 6. Monitoring Data

Dosen atau admin dapat membuka Google Sheets untuk melihat seluruh data presensi secara real-time.

---

# Alur Kerja Sistem

```
Mahasiswa
      │
      ▼
Membuka Website Presensi
(Vercel)
      │
      ▼
Klik Tombol Presensi
atau
Scan QR Code
      │
      ▼
Google Forms
      │
      ▼
Mengisi Data Presensi
      │
      ▼
Submit
      │
      ▼
Google Sheets
(Database Cloud)
      │
      ▼
Admin/Dosen
Melihat Rekap Presensi
```

---

# Implementasi Cloud Computing

## SaaS (Software as a Service)

Platform:

- Google Forms
- Google Sheets

Fungsi:

- Membuat form presensi
- Menyimpan data
- Menampilkan rekap presensi

---

## PaaS (Platform as a Service)

Platform:

- Vercel

Fungsi:

- Hosting website
- Deployment otomatis
- Menyediakan domain website

---

## IaaS (Infrastructure as a Service)

Platform:

- Oracle Cloud Free Tier

Fungsi:

- Server virtual
- Backup data
- Pengembangan sistem di masa depan

---

# Struktur Proyek

```
presensi-cloud/
│
├── index.html
├── qrcode.png
└── README.md
```

---

# Fitur Sistem

✅ Website Presensi Online

✅ QR Code Presensi

✅ Google Forms

✅ Penyimpanan Otomatis

✅ Hosting Cloud

✅ Rekap Data Real-Time

---

# Pengembangan Selanjutnya

Beberapa fitur yang dapat dikembangkan:

- Login Admin
- Login Mahasiswa
- Dashboard Presensi
- Validasi Lokasi (GPS)
- Validasi Waktu
- Export PDF
- Export Excel
- Database MySQL
- API Presensi
- Integrasi Oracle Cloud

---

# Author

Nama : (Nama Anda)

Program Studi Ilmu Komputer

Universitas Pakuan

2026
