
# 🧪 Lab-Dashboard

![CI](https://github.com/Bluefox192/lab-dashboard/actions/workflows/ci.yml/badge.svg)
![Status](https://img.shields.io/badge/status-dev-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Issues](https://img.shields.io/github/issues/Bluefox192/lab-dashboard)
![Last Commit](https://img.shields.io/github/last-commit/Bluefox192/lab-dashboard)
![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)

> **Lab-Dashboard** adalah platform dashboard interaktif untuk memantau progres proyek dan eksperimen secara real-time.  
> Dirancang khusus untuk penggunaan di lingkungan laboratorium, robotika, dan eksperimen fisika.

---

## 🚀 Fitur Utama

- 🔍 **3D Model Viewer** — pratinjau model 3D langsung di browser (STL, GLB).
- 📈 **Grafik Real-Time** — tampilkan data sensor dan log dalam bentuk grafik responsif.
- 🎨 **Tema Dinamis** — mode terang & gelap.
- 🧩 **Modular** — mudah dikembangkan dan disesuaikan dengan kebutuhan proyek.

---

## 🏗️ Status Proyek

> 🚧 **Masih dalam tahap pengembangan awal**  
> Fitur dasar sudah berjalan, namun integrasi sensor, backend, dan konfigurasi dinamis masih dikerjakan.

---

## ⚙️ Teknologi yang Digunakan

- **Frontend**: HTML, CSS, JavaScript
- **3D Viewer**: [`<model-viewer>`](https://modelviewer.dev/)
- **Charting**: Chart.js / Recharts (dalam perencanaan)
- **Tema**: CSS Variables & Toggle Switch

---

## 📅 Roadmap Sementara

- [x] Struktur dasar halaman
- [x] Integrasi viewer 3D
- [ ] Grafik real-time dari data eksternal
- [ ] Backend sederhana (WebSocket / MQTT)
- [ ] Konfigurasi layout dinamis

---

## 📂 Struktur Direktori

```bash
lab-dashboard/
├── assets/         # Model 3D, ikon, gambar
├── components/     # Elemen UI modular
├── css/            # Tema dan styling utama
├── js/             # Script interaktif
├── index.html      # Entry point
└── main/
└── README.md
```

---

## 🧪 GitHub Actions (CI)

Workflow otomatis memeriksa validitas file HTML dan JS saat setiap push ke branch `main`.

File konfigurasi: `.github/workflows/ci.yml`  
Badge status tersedia di atas.

---

## 💬 Kontribusi

Belum terbuka untuk kontribusi publik, tapi semua saran dan masukan sangat diterima!  
Jangan ragu untuk buka [issue](https://github.com/Bluefox192/lab-dashboard/issues) atau diskusi jika ada ide keren 💡

---

## 🧠 Catatan Pribadi

Dibuat oleh Blu ([@Bluefox192](https://github.com/Bluefox192))  
Sebagai bagian dari eksplorasi sistem dashboard mandiri untuk keperluan lab, proyek robotika, dan eksperimentasi IoT.
