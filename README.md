# ⚔️ Magic Chess - Battle Order Tracker

> **Aplikasi web interaktif untuk melacak urutan pertempuran dan status pemain dalam game Magic Chess**

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://manusiakerupukk.github.io/magic-chess-tracker/)

## 🎮 Tentang Aplikasi

**Magic Chess - Battle Order Tracker** adalah aplikasi web sederhana yang membantu pemain Magic Chess untuk:
- 📝 Mencatat daftar 7 musuh dalam match
- 🔄 Mengatur ulang prediksi urutan pertempuran dengan drag & drop
- 🟢 Menandai pemain yang sedang bertarung (fighting mode)
- 💀 Melacak pemain yang sudah dieliminasi
- 💾 Menyimpan data secara otomatis di browser (tidak hilang saat refresh)

## ✨ Fitur Utama

### 1. **Input Nama Musuh**
- Form untuk memasukkan 7 nama musuh
- Validasi input untuk memastikan semua field terisi
- Interface yang clean dan mudah digunakan

### 2. **Drag & Drop Reordering**
- Atur ulang urutan prediksi dengan menyeret item
- Visual feedback saat drag (opacity & border highlight)
- Smooth animations untuk UX yang lebih baik

### 3. **Status Tracking**
- 🟢 **Fighting Mode**: Klik nama pemain untuk tandai sedang bertarung (background hijau)
- 💀 **Kill Button**: Tombol merah untuk menandai pemain eliminated
- ↩️ **Undo Button**: Tombol hijau untuk membatalkan eliminasi (anti misclick!)

### 4. **Persistent Storage**
- Auto-save setiap perubahan ke localStorage browser
- Data tetap tersimpan meskipun browser ditutup atau di-refresh
- Tidak perlu login atau koneksi internet

### 5. **Responsive Design**
- Optimal untuk mobile dan desktop
- Tema gelap dengan aksen amber/gold yang menarik
- Tailwind CSS untuk styling modern

## 🚀 Demo Langsung

**[👉 Coba Aplikasi Di Sini](https://yourusername.github.io/magic-chess-tracker/)**

## 📱 Screenshot

```
┌─────────────────────────┐
│  ⚔️ Magic Chess        │
│  Prediksi Urutan Musuh  │
├─────────────────────────┤
│ 📝 Input 7 Nama Musuh   │
│ 1. [Player 1_____]      │
│ 2. [Player 2_____]      │
│ ...                     │
└─────────────────────────┘

┌─────────────────────────┐
│ 🔮 Atur Urutan Musuh    │
├─────────────────────────┤
│ ☰ 1 Player 1      ↕️    │
│ ☰ 2 Player 2      ↕️    │ (Drag & Drop)
│ ...                     │
├─────────────────────────┤
│ 📊 URUTAN PREDIKSI      │
├─────────────────────────┤
│ 1 Player 1    🥇 [Kill] │ (Klik = Fighting)
│ 2 Player 2    🥈 [Kill] │
│ ...                     │
└─────────────────────────┘
```

## 🎯 Cara Menggunakan

### **Step 1: Input Nama Musuh**
1. Buka aplikasi
2. Masukkan nama 7 musuh di form input
3. Klik tombol **"🎯 Simpan & Mulai Prediksi"**

### **Step 2: Atur Urutan Prediksi**
1. Di section **"🔮 Atur Urutan Musuh"**:
   - Seret dan lepas item untuk mengubah urutan
   - Icon **☰** menandakan item bisa di-drag

### **Step 3: Track Status Pertempuran**
Di section **"📊 URUTAN PREDIKSI"**:

- **Klik nama/nomor pemain** → Tandai sedang bertarung (hijau)
  - Background berubah hijau dengan glow effect
  - Status: "⚔️ Fighting!"
  - Klik lagi untuk cancel

- **Klik tombol "💀 Kill"** → Eliminasi pemain
  - Background berubah merah
  - Nama di-coret
  - Status: "💀 Eliminated"

- **Klik tombol "↩️ Undo"** → Batalkan eliminasi
  - Pemain kembali ke status normal
  - Berguna untuk mengatasi misclick

### **Step 4: Reset (Opsional)**
- Klik tombol **"🔄 Reset"** untuk memulai dari awal
- Semua data akan dihapus dari localStorage

## 💾 Penyimpanan Data

Aplikasi menggunakan **localStorage** browser untuk menyimpan:
- Daftar nama musuh
- Urutan prediksi
- Status eliminated players
- Status fighting player

**Data akan tetap tersimpan sampai Anda:**
- Klik tombol Reset
- Hapus cache browser
- Gunakan mode Incognito/Private (data temporary)

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur aplikasi
- **CSS3** - Styling & animations
- **JavaScript (Vanilla)** - Logic & interaktivity
- **Tailwind CSS** - Utility-first CSS framework
- **LocalStorage API** - Data persistence

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Kontak & Support

- **Issues**: [GitHub Issues](https://github.com/yourusername/magic-chess-tracker/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/magic-chess-tracker/discussions)

## ⭐ Support Project

Jika aplikasi ini berguna, berikan ⭐ di GitHub!

---

**Dibuat dengan ❤️ untuk komunitas Magic Chess**

*Disclaimer: Aplikasi ini tidak berafiliasi dengan Mobile Legends: Bang Bang atau Moonton*