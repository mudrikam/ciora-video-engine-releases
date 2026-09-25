# 🎬 Ciora Video Engine (CVE) — Official Releases & Downloads

<div align="center">

![Ciora Video Engine Banner](https://raw.githubusercontent.com/mudrikam/ciora-video-engine-releases/main/assets/banner.png)

### **Bikin Video Keren Berbasis Kode, Didampingi Asisten AI.**

[![Latest Release](https://img.shields.io/github/v/release/mudrikam/ciora-video-engine-releases?style=flat-square&color=f97316)](https://github.com/mudrikam/ciora-video-engine-releases/releases/latest)
[![Platform Support](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=flat-square)](https://github.com/mudrikam/ciora-video-engine-releases/releases)
[![Built with Tauri](https://img.shields.io/badge/built%20with-Tauri%20v2-24c8db?style=flat-square&logo=tauri&logoColor=white)](https://tauri.app)
[![Powered by Remotion](https://img.shields.io/badge/engine-Remotion-0b84f3?style=flat-square)](https://remotion.dev)
[![Copilot by Hermes](https://img.shields.io/badge/copilot-Hermes%20Copilot-purple?style=flat-square)](https://hermes-agent.nousresearch.com)

**Selamat datang di pusat rilis resmi Ciora Video Engine (CVE)!**  
Di sini kamu bisa mengunduh installer resmi, paket portabel, dan mendapatkan pembaruan otomatis untuk **Windows**, **macOS**, dan **Linux**.

[Unduh Aplikasi](#-unduh-ciora-video-engine) • [Keunggulan Utama](#-keunggulan-ciora-video-engine) • [Panduan Pasang](#-panduan-instalasi-cepat) • [Ekosistem CIORA](https://ciora.id)

---

</div>

## 💡 Keunggulan Ciora Video Engine

Bikin video animasi berkualitas studio sekarang gak harus pusing dengan timeline video manual yang kaku. **Ciora Video Engine** menggabungkan fleksibilitas render berbasis kode (**Remotion React**), kecepatan aplikasi desktop native (**Rust & Tauri v2**), serta kecerdasan asisten AI (**Hermes Copilot**).

| ⚛️ Remotion Engine | 🦀 Rust Native Core | 🧠 Hermes Copilot |
| :--- | :--- | :--- |
| **Animasi Berbasis Kode**<br>Render komponen React & CSS menjadi video frame-by-frame | **Ngebut & Hemat Memori**<br>Biner desktop native super ringan tanpa membebani RAM | **Asisten AI Terintegrasi**<br>Bantu racik scene, alur komposisi, dan timeline otomatis |

- ⚡ **Ringan & Hemat Memori:** Dibangun langsung di atas mesin native Rust, bukan browser berat yang memakan banyak RAM.
- 🎨 **Animasi Presisi Berbasis Kode:** Kendalikan pergerakan teks, transisi scene, tipografi kinetik, dan grafis visual frame-by-frame dengan akurasi tinggi.
- 🤖 **Hermes Copilot Siap Membantu:** Cukup ketik ide atau instruksimu di panel chat, asisten AI langsung meracik kode scene, komposisi, dan asetnya untukmu.
- 🔄 **Update Mulus Otomatis:** Persis seperti VS Code, kamu gak perlu repot download ulang installer setiap ada fitur baru. Aplikasi akan memperbarui dirinya sendiri di latar belakang!

---

## 🚀 Unduh Ciora Video Engine

Pilih installer sesuai sistem operasi yang kamu gunakan:

### 🪟 Windows (Windows 10 / 11 — 64-bit)
| Format | Tipe | Tautan Unduh |
| :--- | :--- | :--- |
| **`.exe` (Setup)** | Installer Standar (Direkomendasikan) | [Unduh Windows Setup (x64)](https://github.com/mudrikam/ciora-video-engine-releases/releases/latest) |
| **`.zip` (Portable)** | Tanpa Install, Ekstrak & Jalankan Langsung | [Unduh Windows Portable (x64)](https://github.com/mudrikam/ciora-video-engine-releases/releases/latest) |

### 🍏 macOS (macOS 12 Monterey ke atas)
| Arsitektur | Tipe | Tautan Unduh |
| :--- | :--- | :--- |
| **Apple Silicon (M1/M2/M3/M4)** | `.dmg` Installer Native ARM64 | [Unduh macOS Apple Silicon](https://github.com/mudrikam/ciora-video-engine-releases/releases/latest) |
| **Intel Mac (x86_64)** | `.dmg` Installer Intel 64-bit | [Unduh macOS Intel](https://github.com/mudrikam/ciora-video-engine-releases/releases/latest) |

### 🐧 Linux (Ubuntu, Debian, Fedora, Arch, dll.)
| Format | Tipe | Tautan Unduh |
| :--- | :--- | :--- |
| **`.AppImage`** | Portabel Mandiri (Jalankan di semua distro) | [Unduh Linux AppImage](https://github.com/mudrikam/ciora-video-engine-releases/releases/latest) |
| **`.deb`** | Paket Resmi Debian / Ubuntu | [Unduh Linux Debian Package](https://github.com/mudrikam/ciora-video-engine-releases/releases/latest) |

---

## 🛠️ Panduan Instalasi Cepat

### 🪟 Di Windows:
1. Unduh berkas `Ciora-Video-Engine-Setup-x64.exe`.
2. Klik ganda untuk memulai instalasi, ikuti instruksi singkat di layar.
3. Buka **Ciora Video Engine** dari Start Menu atau Desktop!

### 🍏 Di macOS:
1. Unduh berkas `.dmg` sesuai prosesor Mac kamu (Apple Silicon atau Intel).
2. Buka berkas `.dmg`, lalu seret ikon **Ciora Video Engine** ke folder **Applications**.
3. Jika muncul peringatan keamanan saat pertama dibuka, buka *System Settings* > *Privacy & Security*, lalu klik *Open Anyway*.

### 🐧 Di Linux:
```bash
# Untuk format AppImage:
chmod +x ciora-video-engine_amd64.AppImage
./ciora-video-engine_amd64.AppImage

# Atau untuk format .deb:
sudo dpkg -i ciora-video-engine_amd64.deb
```

---

## 🔄 Cara Kerja Pembaruan Otomatis (*Auto-Update*)

Kamu tidak perlu mengecek halaman rilis ini setiap hari untuk mendapatkan fitur atau perbaikan bug terbaru:

1. **Pemeriksaan Senyap:** Saat kamu menjalankan aplikasi, CVE memeriksa pembaruan biner terbaru di latar belakang secara aman.
2. **Unduhan di Balik Layar:** Jika ada versi baru, berkas akan diunduh secara diam-diam tanpa mengganggu pekerjaan videomu.
3. **Penerapan Otomatis:** Saat aplikasi ditutup dan kamu membukanya lagi nanti, CVE sudah otomatis berjalan di versi paling anyar, lengkap dengan rangkuman *"Apa yang baru"*!

---

## 📦 Dependensi & Keterbukaan Sumber Daya (*Open Source Disclosure*)

Ciora Video Engine berdiri di atas pundak ekosistem *open-source* dan teknologi kelas dunia. Sebagai bentuk apresiasi, transparansi, dan kepatuhan terhadap lisensi, berikut adalah teknologi inti yang menggerakkan CVE beserta tautan repositori resminya:

| Proyek / Dependensi | Lisensi | Peran di CVE | Tautan Repositori Resmi |
| :--- | :--- | :--- | :--- |
| **Tauri v2** | Apache-2.0 / MIT | Fondasi desktop native, manajemen jendela, IPC bridge, dan sistem auto-update | [github.com/tauri-apps/tauri](https://github.com/tauri-apps/tauri) |
| **Remotion** | Remotion License | Engine rendering animasi, manajemen frame, dan komposisi video berbasis kode React | [github.com/remotion-dev/remotion](https://github.com/remotion-dev/remotion) |
| **Hermes Agent** | MIT | Asisten AI otonom (*Copilot*) untuk pembuatan scene, skrip, dan otomasi alur video | [github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) |
| **FFmpeg** | LGPL 2.1+ / GPL | Biner native encoding/muxing performa tinggi untuk konversi video ke MP4, WebM, ProRes | [github.com/FFmpeg/FFmpeg](https://github.com/FFmpeg/FFmpeg) |
| **Node.js** | MIT | Runtime JavaScript lokal untuk mengeksekusi Remotion dev server dan bundler | [github.com/nodejs/node](https://github.com/nodejs/node) |
| **React** | MIT | Framework antarmuka pengguna untuk player studio dan kanvas video interaktif | [github.com/facebook/react](https://github.com/facebook/react) |
| **Vite** | MIT | Build tool dan Hot Module Replacement (HMR) sub-detik untuk live preview video | [github.com/vitejs/vite](https://github.com/vitejs/vite) |
| **Lucide Icons** | ISC | Kumpulan ikon grafis elegan yang digunakan di seluruh panel antarmuka CVE | [github.com/lucide-icons/lucide](https://github.com/lucide-icons/lucide) |

*Seluruh hak cipta, merek dagang, dan kepemilikan intelektual dari proyek-proyek di atas tetap menjadi milik masing-masing pencipta dan kontributor aslinya.*

---

## 🤝 Komunitas & Dukungan

Ada pertanyaan, butuh bantuan seputar workflow video, atau ingin berbagi karya animasi yang kamu buat?

- 🌐 **Website Resmi:** [ciora.id](https://ciora.id)
- 💬 **Komunitas Telegram:** [Desainia Studio Community](https://t.me/desainia_community)
- 📖 **Dokumentasi & API:** [ciora.id/docs](https://ciora.id/docs)
- 🐛 **Laporkan Kendala / Bug:** Buka tiket di tab [Issues](https://github.com/mudrikam/ciora-video-engine-releases/issues)

---

<div align="center">

Dibuat dengan dedikasi dan cinta untuk para kreator programmatic video oleh **CIORA Team**.  
*© 2026 CIORA. All rights reserved.*

</div>
