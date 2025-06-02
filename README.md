# 📱 SIPRASA (Sistem Pelaporan Sarana Publik Surakarta)

SIPRASA adalah aplikasi Android berbasis Java yang dirancang untuk membantu masyarakat Surakarta dalam melaporkan kerusakan infrastruktur publik secara cepat dan efisien. Dengan sistem pelaporan yang terintegrasi ke backend berbasis RESTful API (Express.js & MongoDB), aplikasi ini mendukung penanganan masalah infrastruktur secara lebih responsif dan transparan.

---

## 📌 Latar Belakang

Surakarta sebagai kota wisata dan pendidikan menghadapi tantangan besar dalam hal pemeliharaan infrastruktur publik. Keterbatasan sumber daya dan tidak adanya sistem pelaporan yang partisipatif menyebabkan lambatnya penanganan kerusakan fasilitas umum.

SIPRASA hadir sebagai solusi digital untuk:
- Meningkatkan partisipasi masyarakat dalam menjaga fasilitas publik
- Mempercepat proses pelaporan dan penanganan kerusakan
- Mendukung pengelolaan kota yang lebih transparan dan efisien

---

## 🎯 Alasan Pemilihan Project

- **Relevansi Lokal**  
  Infrastruktur di Surakarta sering rusak dan lambat ditangani karena belum tersedianya sistem pelaporan yang efektif.
  
- **Penerapan Teknologi Digital**  
  Web dan mobile-based reporting system terbukti meningkatkan efisiensi manajemen informasi dan respon terhadap aduan publik.

---

## 🚀 Hasil Project

SIPRASA memungkinkan warga untuk:
- 📸 Mengunggah laporan disertai foto dan lokasi
- 🗂 Memilih kategori kerusakan (jalan, jembatan, taman, dll.)
- 📝 Menjelaskan kronologi kerusakan
- 📊 Melihat daftar laporan yang dikirim dan statusnya
- 🔔 Mendapat notifikasi jika laporan diproses atau selesai

Data laporan akan dikelola oleh pihak berwenang melalui sistem backend yang mendukung pengelolaan laporan berbasis status.

---

## 🧩 Fitur yang Diimplementasikan

| Fitur             | Deskripsi                                                                 |
|-------------------|---------------------------------------------------------------------------|
| 📦 **Database (Room)** | Menyimpan data pengguna dan cache data laporan secara lokal.               |
| 🧱 **Fragment**        | Digunakan untuk membangun struktur UI modular (Dashboard, Form, dll).     |
| 📡 **BroadcastReceiver** | Mendeteksi status jaringan & baterai secara real-time.                      |
| 🔊 **Service**         | Memutar suara saat aplikasi dibuka dan ketika laporan berhasil dikirim. |

---

## 🧱 Teknologi yang Digunakan

### 📱 Android (Java)
- Activity & Fragment Lifecycle
- RecyclerView
- Room Database
- Retrofit (Networking)
- Volley (Upload Multipart)
- SharedPreferences (Auth Token)
- Glide (Image Loader)
- BroadcastReceiver (Network & Battery)
- Service (Audio Feedback)
- Intent, Bundle, DatePicker

### 🌐 Backend (REST API)
- Express.js
- MongoDB
- Multer (Image Upload)
- JWT Authentication
- CORS & Routing Middleware

---

## 🧑‍💻 Tim Pengembang

| Nama                         | NIM         |
|------------------------------|-------------|
| Almira Putri Wibowo          | L200220068  |
| Diah Ayu Susilowati          | L200220066  |
| Luthfiana Azzalea Afifah     | L200220052  |

---

## 📷 Screenshot Aplikasi

![image](https://github.com/user-attachments/assets/9bf78067-5f53-4703-be92-25d862996354)

---

## 📌 Lisensi

Proyek ini dibuat untuk tujuan pembelajaran dan pengembangan. Semua hak cipta sepenuhnya milik tim pengembang.
