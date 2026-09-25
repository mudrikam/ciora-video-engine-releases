# 🎬 Ciora Video Engine (CVE) — Official Releases & Downloads

<div align="center">

![Ciora Video Engine Banner](https://raw.githubusercontent.com/mudrikam/ciora-video-engine-releases/main/assets/banner.png)

### **Programmatic Video Creation Meets Agentic Intelligence.**

[![Latest Release](https://img.shields.io/github/v/release/mudrikam/ciora-video-engine-releases?style=flat-square&color=f97316)](https://github.com/mudrikam/ciora-video-engine-releases/releases/latest)
[![Platform Support](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=flat-square)](https://github.com/mudrikam/ciora-video-engine-releases/releases)
[![Built with Tauri](https://img.shields.io/badge/built%20with-Tauri%20v2-24c8db?style=flat-square&logo=tauri&logoColor=white)](https://tauri.app)
[![Powered by Remotion](https://img.shields.io/badge/engine-Remotion-0b84f3?style=flat-square)](https://remotion.dev)
[![Copilot by Hermes](https://img.shields.io/badge/copilot-Hermes%20Agent-purple?style=flat-square)](https://hermes-agent.nousresearch.com)

**Selamat datang di pusat rilis resmi Ciora Video Engine (CVE)!**  
Repositori ini adalah rumah tempat seluruh paket biner instalasi, rilis portabel, serta saluran pembaruan otomatis (*autonomous background updater*) untuk sistem operasi **Windows**, **macOS**, dan **Linux** didistribusikan secara resmi.

[Unduh Versi Terbaru](#-unduh-ciora-video-engine) • [Fitur Unggulan](#-kenapa-ciora-video-engine) • [Cara Pasang](#-panduan-instalasi-cepat) • [Ekosistem CIORA](https://ciora.id)

---

</div>

## ✨ Kenapa Ciora Video Engine?

Bikin video berkualitas studio gak harus ribet dengan timeline video konvensional yang kaku. **Ciora Video Engine** menggabungkan kekuatan rendering berbasis kode (**Remotion React**), arsitektur desktop bertenaga biner native (**Rust & Tauri v2**), serta pendampingan asisten AI otonom (**Hermes Agent Copilot**).

```text
  ┌────────────────────────────────────────────────────────────────────────┐
  │                        CIORA VIDEO ENGINE                              │
  ├───────────────────────┬───────────────────────┬────────────────────────┤
  │   ⚛️ Remotion Engine  │   🦀 Rust Native Core │   🧠 Hermes AI Copilot │
  │   Render video via    │   Super ringan, hemat │   Bikin animasi & alur │
  │   kode React & Web    │   RAM & CPU hardware  │   video via instruksi  │
  └───────────────────────┴───────────────────────┴────────────────────────┘
```

- ⚡ **Super Ringan & Hemat RAM:** Dibangun di atas fondasi native Rust tanpa bloatware browser berat.
- 🎨 **Programmatic Video:** Render animasi teks, kinetic typography, grafik, dan motion design dengan presisi frame-by-frame.
- 🤖 **Hermes Copilot Terintegrasi:** Bicara langsung dengan asisten AI di sidebar untuk membuat scene, menulis skrip komposisi, atau memodifikasi timeline secara instan.
- 🔄 **Seamless Silent Update:** Mirip VS Code, kamu gak perlu repot download ulang installer saat ada fitur baru. Aplikasi akan memperbarui dirinya secara otomatis dan siap dipakai!

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
