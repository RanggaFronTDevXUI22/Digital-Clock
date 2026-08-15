# Digital-Clock

# 🕐 Digital Clock

Aplikasi jam digital real-time yang indah dan responsif dengan desain modern.

## 📋 Fitur Utama

- ⏰ **Jam Real-Time** - Menampilkan waktu yang selalu diperbarui setiap detik
- 🎨 **Desain Modern** - Interface yang elegan dengan gradien warna dan efek glassmorphism
- 📱 **Responsif** - Berfungsi sempurna di desktop, tablet, dan mobile
- ✨ **Animasi** - Separator jam yang berkedip halus untuk visual yang menarik
- 🎯 **Akurat** - Menampilkan jam 12-jam dengan indikator AM/PM

## 🚀 Cara Menggunakan

1. **Buka file** `index.html` di browser favorit Anda
2. Jam akan menampilkan waktu saat ini secara otomatis
3. Waktu akan diperbarui setiap detik

## 📂 Struktur File

```
Digital-Clock/
├── index.html      # File HTML utama
├── style.css       # Stylesheet dengan desain responsif
├── app.js          # JavaScript untuk logika jam
└── README.md       # File dokumentasi ini
```

## 💻 Teknologi yang Digunakan

- **HTML5** - Struktur dasar aplikasi
- **CSS3** - Styling dengan gradien, animasi, dan backdrop filter
- **JavaScript (Vanilla)** - Logika untuk update jam real-time

## 🎨 Desain

### Warna Tema
- **Background**: Gradien biru gelap (navy to teal)
- **Clock Box**: Gradien ungu (indigo to purple)
- **AM/PM**: Gradien merah muda (pink to red)
- **Separator**: Warna ungu terang dengan efek berkedip

### Fitur Visual
- ✨ Glassmorphism effect pada container
- 🌟 Box shadow yang memberikan depth
- 🎭 Hover effect yang subtle pada jam
- 📐 Border radius yang smooth

## 🔧 Kustomisasi

### Mengubah Warna
Edit bagian warna di `style.css`:
```css
/* Untuk gradient jam utama */
.clock span {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

/* Untuk AM/PM */
.clock #ampm {
    background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
}
```

### Mengubah Ukuran Font
```css
/* Untuk angka jam */
.clock span {
    font-size: 48px; /* Ubah nilai ini */
}
```

## 📱 Responsive Breakpoints

- **Desktop** (> 768px): Ukuran penuh dengan spacing optimal
- **Mobile** (< 768px): Ukuran yang disesuaikan agar pas di layar kecil

## ⚙️ Sistem Waktu

- Menggunakan format **12-jam** (1-12)
- Menampilkan **AM/PM** untuk membedakan pagi dan sore
- Detik diperbarui secara real-time setiap 1000ms (1 detik)

## 🐛 Troubleshooting

**Jam tidak berjalan?**
- Pastikan JavaScript diaktifkan di browser
- Cek console browser (F12) untuk error messages

**Tampilan tidak responsif?**
- Refresh browser
- Periksa apakah meta viewport tag ada di HTML

## 📝 Lisensi

Gratis untuk digunakan dan dimodifikasi sesuai kebutuhan Anda.

## 👨‍💻 Pengembang

Dibuat dengan ❤️ menggunakan HTML, CSS, dan JavaScript

---

**Selamat menggunakan Digital Clock! 🕐✨**