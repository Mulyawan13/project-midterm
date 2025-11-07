# Project Midterm

<img width="1385" height="797" alt="image" src="https://github.com/user-attachments/assets/dc9ab37b-ac1a-45c7-a8e4-54dd9a0bcee3" />


## 🚀 Fitur Utama

### 🗺️ Peta Choropleth
- Menampilkan distribusi **kasus baru, kematian baru, total kasus, dan total kematian** per provinsi.
- Warna menunjukkan intensitas kasus (merah = tinggi, hijau = rendah).
- Dapat di-*zoom* dan *pan*, serta menampilkan **tooltip detail** saat hover.
- Klik provinsi untuk membuka **modal detail provinsi** berisi data lengkap dan mini map.

### 📈 Grafik Timeline Interaktif
- Dilengkapi **tooltip dinamis** dan **brush** untuk memfilter rentang tanggal.
- Ada **anotasi naratif** untuk puncak gelombang Delta (2021) dan Omicron (2022).

### ⏯️ Kontrol Waktu & Animasi
- Slider waktu + tombol **Play/Pause** untuk menjelajahi data per tanggal.
- Animasi halus antar frame untuk memperlihatkan perubahan tren waktu ke waktu.

### 📊 Ringkasan Key Perfomance Indicator
- Menampilkan angka nasional terkini:
  - Kasus Baru
  - Kematian Baru
  - Total Kasus
  - Total Kematian

## 🧠 Teknologi yang Digunakan
- [D3.js v7](https://d3js.org/) — library utama untuk visualisasi interaktif berbasis SVG.
- **HTML5 + CSS3** — layout & gaya antarmuka.
- **GeoJSON** — data batas wilayah provinsi Indonesia.
- **JavaScript (ES6)** — logika, event handling, dan animasi.

