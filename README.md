# 🧮 pbk-warung-app

aplikasi **Manajemen Warung Madura** yang dibangun menggunakan Vue.js sebagai tugas uas mata kuliah Pemrograman Berbasis Komponen (PBK).

## ✨ Fitur Aplikasi

- Login user (admin)
- CRUD barang dan filter kategori
- Keranjang belanja & transaksi otomatis
- Riwayat transaksi
- Statistik barang per kategori (chart)


## 🧰 Teknologi

- Vue 3 + Vite
- Vue Router
- Pinia (state management)
- Axios (API call)
- Chart.js (grafik)
- json-server (backend API)
- Vitest (@vue/test-utils)

## 🌐 Backend API

Gunakan endpoint:  
[https://pbk-warung-api.onrender.com/api](https://pbk-warung-api.onrender.com/api)

Contoh:  
- `GET /api/barang`  
- `POST /api/transaksi`

## ▶️ Menjalankan Secara Lokal

```bash
npm install
npm run dev
