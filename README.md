# Dzikr Counter PWA 📿

Dzikr Counter adalah aplikasi web sederhana berbasis **Progressive Web App (PWA)** yang dirancang untuk memudahkan pengguna dalam menghitung dzikir sehari-hari melalui *smartphone*. 

Aplikasi ini sangat ringan, tidak mengandung iklan, dan dirancang dengan antarmuka gelap (Dark Mode) agar nyaman digunakan di malam hari atau dalam kondisi minim cahaya.

## ✨ Fitur Utama

- 📱 **Bisa Diinstal (PWA):** Dapat ditambahkan langsung ke layar utama (Home Screen) *smartphone* layaknya aplikasi *native* tanpa perlu lewat App Store / Play Store.
- 🔌 **Dukungan Offline:** Setelah diakses pertama kali, aplikasi tetap bisa digunakan kapan saja meski tanpa koneksi internet (menggunakan Service Worker).
- 💾 **Auto-Save:** Hitungan tidak akan hilang meskipun aplikasi ditutup atau browser di-*refresh* (menggunakan `localStorage`).
- 📳 **Haptic Feedback:** Memberikan getaran halus (vibrasi) setiap kali layar diketuk, meniru sensasi menggunakan tasbih fisik (pada perangkat yang mendukung).
- 👆 **Tap Bebas:** Seluruh area layar berfungsi sebagai tombol *counter*, sehingga Anda tidak perlu melihat layar untuk memencet tombol secara akurat.
- 🌑 **Tema Gelap:** Melindungi mata dari kelelahan akibat cahaya layar yang terlalu terang.

## 🚀 Cara Instalasi (Pengguna)

Karena aplikasi ini adalah PWA, Anda tidak perlu mengunduhnya dari toko aplikasi. Cukup ikuti langkah berikut:

1. Buka tautan aplikasi (misalnya: `https://[username-github-anda].github.io/[nama-repo]/`) melalui browser (Chrome/Safari) di *smartphone* Anda.
2. Tunggu beberapa detik hingga muncul *popup* atau *banner* di bawah layar bertuliskan **"Add to Home Screen"** (Tambahkan ke Layar Utama).
3. Jika *banner* tidak muncul, klik ikon titik tiga (di Chrome) atau ikon *Share* (di Safari), lalu pilih menu **"Add to Home Screen"**.
4. Aplikasi Dzikr Counter akan muncul di layar *smartphone* Anda dan siap digunakan secara *offline*!

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun murni menggunakan teknologi web standar tanpa *framework* agar tetap ringan dan cepat:
- **HTML5** untuk struktur halaman.
- **CSS3 (Vanilla)** untuk tampilan (UI/UX) dan *styling*.
- **Vanilla JavaScript** untuk logika *counter* dan fitur haptic.
- **Service Workers & Web App Manifest** untuk fungsionalitas PWA dan *Offline Cache*.

## 📂 Struktur File

```text
.
├── index.html       # Tampilan utama dan logika JavaScript aplikasi
├── manifest.json    # Konfigurasi PWA (nama, warna tema, identitas aplikasi)
├── sw.js            # Service Worker untuk cache file agar bisa offline
├── icon-192.png     # Ikon aplikasi resolusi standar
├── icon-512.png     # Ikon aplikasi resolusi tinggi
└── README.md        # Dokumentasi proyek
```

## 🌐 Cara Hosting (Developer)

Jika Anda ingin meng-*hosting* aplikasi ini sendiri (fork/clone repo ini):

1. *Upload* seluruh file ke *repository* GitHub Anda.
2. Buka tab **Settings** di *repository* tersebut.
3. Masuk ke menu **Pages** di sebelah kiri.
4. Pada bagian *Source*, pilih *branch* `main` atau `master`.
5. Klik **Save**. Tunggu beberapa menit, dan aplikasi Anda akan *live* di tautan GitHub Pages yang disediakan.

---
*Dibuat untuk memudahkan ibadah harian Anda.*