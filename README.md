# Pustaka Hadits Indonesia 🕌

![React](https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react)
![TailwindCSS](https://img.shields.io/badge/Style-Tailwind-38bdf8?style=for-the-badge&logo=tailwindcss)
![Supabase](https://img.shields.io/badge/Backend-Supabase-emerald?style=for-the-badge&logo=supabase)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

**Pustaka Hadits Indonesia** adalah ensiklopedia hadits digital berbasis web yang dirancang untuk memudahkan umat Muslim mencari, membaca, dan membagikan hadits shahih. Aplikasi ini dibangun dengan React.js dan terhubung langsung ke database cloud Supabase, menawarkan antarmuka yang modern, responsif, dan kaya fitur.

🔗 **Live Demo:** [Lihat Website](https://pustaka-hadits-indonesia.vercel.app/).

---

## ✨ Fitur Unggulan

### 📚 Koleksi Lengkap (Kutubus Sittah + Malik)
Akses mudah ke 7 kitab hadits utama dengan filter instan:
* Shahih Bukhari & Muslim
* Sunan Abu Dawud, An-Nasa'i, Ibnu Majah
* Jami' At-Tirmidzi
* Muwatta Malik

### 🔍 Pencarian & Filter Cerdas
* **Real-time Search:** Cari hadits berdasarkan kata kunci (Indonesia/Arab) langsung ke database server-side.
* **Smart Enrichment:** Algoritma otomatis yang mendeteksi **Topik** (Shalat, Puasa, Akhlak, dll) dan **Perawi Utama** dari teks hadits jika data di database belum lengkap.

### 🛠️ Utilitas Pengguna
* **Copy & Share:** Salin teks hadits atau bagikan langsung ke media sosial via Web Share API.
* **Modal Baca:** Tampilan popup yang nyaman dan fokus untuk membaca detail hadits.
* **SEO Manager:** Meta tags otomatis untuk optimasi mesin pencari dan preview media sosial (Open Graph).

### 🎨 Antarmuka Modern
* **Desain Responsif:** Tampilan optimal di Desktop maupun Mobile.
* **Tipografi Islami:** Menggunakan font *Amiri* untuk teks Arab dan *Inter* untuk terjemahan.
* **Tema Emerald:** Palet warna hijau yang menyejukkan mata.

---

## 🛠️ Teknologi

* **Frontend Library:** [React 18](https://reactjs.org/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **Icons:** [Lucide React](https://lucide.dev/)
* **Backend / Database:** [Supabase](https://supabase.com/) (PostgreSQL via REST API)
* **Data Fetching:** Native Fetch API

---

## 🚀 Cara Menjalankan di Lokal

Ikuti langkah-langkah ini untuk menjalankan proyek di komputer Anda:

### 1. Clone Repository
```bash
git clone [https://github.com/azfaribn/pustaka-hadits-indonesia.git](https://github.com/azfaribn/pustaka-hadits-indonesia.git)
cd pustaka-hadits-indonesia
