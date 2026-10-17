# Bloodborne Indonesian Translation (Native PC Port)

![Status](https://img.shields.io/badge/Status-Released-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Native%20PC%20Port-blue)
![Region](https://img.shields.io/badge/Region-CUSA03173%20(EU)-green)
![Language](https://img.shields.io/badge/Language-Bahasa%20Indonesia-red)

Mod terjemahan Bahasa Indonesia untuk **Bloodborne Native PC Port (`bbport`)**.

Proyek ini bertujuan memberikan pengalaman bermain yang lebih imersif bagi para Hunter Indonesia melalui terjemahan yang mempertahankan atmosfer *Dark Fantasy*, horor Gotik, dan *Cosmic Horror* khas Bloodborne.

## ✨ Fitur Utama

- **UI & Menu**: Terjemahan menu, pengaturan, dan teks antarmuka.
- **Dialog & NPC**: Terjemahan percakapan karakter dan teks yang berkaitan dengan lore.
- **Item & Deskripsi**: Terjemahan deskripsi senjata, perlengkapan, dan item dengan gaya bahasa yang sesuai dengan atmosfer game.
- **Blood Messages**: Terjemahan pesan pemain yang ditemukan di sepanjang permainan.
- **Konsistensi Terminologi**: Nama item, *Blood Echoes*, *Insight*, *Hunter's Dream*, *Caryll Runes*, serta nama lokasi tertentu tetap menggunakan Bahasa Inggris untuk mempertahankan identitas dan nuansa asli Bloodborne.

## ⚠️ Kompatibilitas

- **Game**: Bloodborne Native PC Port (`bbport`).
- **Region**: Diuji pada CUSA03173 (Europe / GOTY Edition).
- **Bahasa**: English (UK) atau English (US), sesuai dengan folder bahasa yang digunakan.
- **Platform**: Linux x86-64 dengan lingkungan runtime yang didukung oleh `bbport`.

> **Catatan:** Kompatibilitas dengan region atau konfigurasi game lainnya belum tentu terjamin. Pastikan file terjemahan sesuai dengan struktur direktori instalasi yang digunakan.

## 📥 Cara Instalasi

### 1. Unduh mod

Unduh file `.zip` terbaru melalui halaman **[Releases](../../releases)** pada repositori ini.

### 2. Ekstrak file

Ekstrak arsip yang telah diunduh. Pastikan folder hasil ekstraksi dapat diakses sebelum melanjutkan instalasi.

### 3. Backup file asli

**WAJIB:** Salin folder `msg` asli dari instalasi game dan simpan di lokasi yang aman sebelum mengganti file apa pun.

Backup ini diperlukan untuk memulihkan file asli jika terjadi masalah.

### 4. Salin file terjemahan

Buka folder `CUSA03173` dari hasil ekstraksi. Salin folder `msg`, atau folder bahasa yang sesuai (`enggb` / `engus`) jika tersedia, ke direktori berikut:

```text
Bloodborne/
└── CUSA03173/
    └── dvdroot_ps4/
        └── msg/
```

Sesuaikan lokasi direktori dengan struktur instalasi `bbport` yang kamu gunakan. Jangan menimpa folder lain di luar cakupan mod.

### 5. Timpa file

Jika sistem meminta konfirmasi, pilih **Replace** untuk mengganti file yang sesuai dengan file terjemahan.

### 6. Jalankan game

Jalankan Bloodborne melalui `bbport` dan periksa apakah terjemahan telah diterapkan dengan benar.

### Catatan untuk region US

Untuk game region US **CUSA00900**, file `.dcx` mungkin perlu ditempatkan di folder `engus` yang sesuai.

Dukungan region US belum dijamin. Selalu buat backup sebelum melakukan perubahan.

## 🐛 Melaporkan Bug atau Typo

Jika menemukan masalah terjemahan, silakan buat laporan melalui halaman **[Issues](../../issues)**.

Jenis laporan yang dapat dikirimkan meliputi:

- Typo atau kesalahan terjemahan.
- Teks yang belum diterjemahkan.
- Teks terpotong atau keluar dari batas antarmuka (*out of bounds*).
- Istilah yang tidak konsisten.
- Teks yang tidak tampil sebagaimana mestinya.

Sertakan informasi berikut agar masalah lebih mudah ditelusuri:

- Lokasi teks di dalam game.
- Screenshot yang menunjukkan masalah.
- Region game yang digunakan.
- Informasi tambahan mengenai konfigurasi atau versi port jika relevan.

## 🙏 Kredit dan Ucapan Terima Kasih

Proyek ini terbantu oleh berbagai tool dan kontribusi komunitas:

- **FromSoftware & Sony Interactive Entertainment**: Pengembang dan pemegang hak kekayaan intelektual Bloodborne.
- **[Smithbox](https://github.com/vawser/Smithbox)**: Tool modding untuk mengelola dan mengedit data teks FMG.
- **BinderTool / Yabber**: Tool pendukung untuk ekstraksi dan pengelolaan file game.
- **Claude AI**: Asisten dalam proses penerjemahan teks dari Bahasa Inggris ke Bahasa Indonesia.
- **Komunitas Modding Bloodborne PC**: Komunitas yang mendukung pengembangan dan eksplorasi teknis Bloodborne di PC.

## ⚖️ Disclaimer

Proyek ini merupakan modifikasi buatan penggemar (*fan-made*) dan tidak berafiliasi dengan, didukung oleh, atau secara resmi terkait dengan FromSoftware maupun Sony Interactive Entertainment.

Seluruh hak atas Bloodborne, termasuk game, karakter, aset, dan teks aslinya, tetap menjadi milik pemegang hak masing-masing.

Mod ini didistribusikan secara gratis dan tidak dimaksudkan untuk diperjualbelikan.

---

*Dibuat untuk para Hunter Indonesia.*

**Fear the Old Blood.**
