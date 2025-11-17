# ⚡ Macan Fusion Suite  
### *Where Media Meets System Intelligence*  
Part of the **Macan Angkasa Ecosystem** — engineered by **Danx Exodus**

---

## 🧩 Overview  
**Macan Fusion Suite** represents the seamless integration of **multimedia innovation** and **system engineering precision.**  
It combines advanced playback, conversion, downloading, and system management tools — unified under one professional-grade ecosystem.  

Designed with performance, stability, and modularity in mind, each component in this suite delivers enterprise-level functionality while maintaining the creative and elegant design language that defines **Macan Angkasa**.

---

## 📸 Screenshot
<img width="2048" height="2665" alt="macan-fusion-suite" src="https://github.com/user-attachments/assets/f5d9bb00-2967-42f8-99b8-15e7e82c370e" />
---
## Changelog v2.4.0
1. Macan Converter Pro v4.0.0 - 5.0.0
- ✨ New Features
Advanced Video Conversion: A new "Advanced Options" panel has been added, giving users granular control over:
Video Bitrate & FPS
Video Encoder (e.g., libx264, libx265, vp9)
Audio Encoder (e.g., aac, libmp3lame, ac3)
Audio Sample Rate, Bitrate, and Channels (Mono/Stereo)
Video Preset System:
Users can now save their custom advanced configurations as a named preset.
Saved presets can be easily loaded from a dropdown menu for future use.
The system automatically detects manual changes and switches to a "-- Custom --" state.
Dynamic Encoders: The Video Encoder list now intelligently updates based on the selected output container (e.g., MP4 and MKV will show different encoder options).

- 🖥️ UI/UX Improvements
Video Tab Redesign: The Video options panel has been completely rebuilt using a QSplitter.
Collapsible Panel: The "Advanced Options" checkbox now toggles the visibility of the new panel in a clean, expandable splitter layout, replacing the old layout.
Window & Layout:
The main window's default and minimum size has been increased to better accommodate the new options.
Minor stylesheet padding was adjusted for a tighter UI.

- ⚙️ Backend & Core
VideoConversionWorker: The worker class has been fundamentally upgraded to accept and process all new advanced parameters (is_advanced, v_bitrate, fps, v_encoder, etc.) and build the correct FFMPEG command.
Settings Persistence: The _save_settings and _load_settings functions now store all advanced video settings and saved user presets in QSettings, ensuring they persist between sessions.
Localization: All new UI elements and dialog boxes (e.g., "Save Preset") have been added to the multi-language dictionary for both Indonesian and English.
---


## 💼 Core Components  

| Application | Description |
|--------------|-------------|
| 🎬 **Macan Super Video** | A next-generation video player built on the MPC-HC core, providing precise playback control and superior performance. |
| 📺 **Macan VLC** | A universal media player powered by the VLC engine with native support for streaming, subtitles, and thumbnail rendering. |
| 🔄 **Macan Converter Pro** | A powerful transcoding utility supporting multiple formats and hardware acceleration for seamless conversion workflows. |
| 🌐 **Macan Video Downloader – Mystic Edition** | A modern downloader capable of fetching and parsing video content from various online sources with precision and elegance. |
| 📁 **Macan Explorer** | A lightweight, advanced file manager supporting network drives, mapping, and visual navigation for Windows environments. |
| 🧰 **Macan Conquer (Windows Toolkit)** | A collection of system utilities designed for advanced users and engineers to diagnose, control, and optimize system operations. |

---

## ⚙️ Architecture Philosophy  
The **Fusion Suite** was built under a unified design principle — **“Integration Through Independence.”**  
Each application operates as a standalone tool but shares the same:
- UI/UX consistency (modern, flat, and responsive design)  
- Core logic standards (performance-optimized Python & Qt modules)  
- Configuration structure  
- Branding and identity under the Macan Angkasa umbrella  

> *Every tool is independent — yet collectively powerful.*

---

## 🚀 Key Features
✅ Unified interface and aesthetic consistency across all applications  
✅ Optimized for Windows, supporting native API integration and drive mapping  
✅ Hardware-accelerated video playback and conversion  
✅ Modular core architecture for easy feature expansion  
✅ Clean, efficient codebase — no unnecessary dependencies  
✅ Built-in update and configuration systems  

---

## 🏗️ Technical Overview

| Stack | Purpose |
|-------|----------|
| **Python 3.9+** | Core development language |
| **PySide6 / PyQt6** | GUI framework and system integration |
| **FFmpeg / VLC / MPC-HC Core** | Media and transcoding backends |
| **OpenCV** | Thumbnail and frame extraction |
| **QSettings / JSON** | Persistent configuration storage |
| **Subprocess & Threading** | Concurrent task handling |

---

## 🔮 Vision & Philosophy  
**Macan Fusion Suite** embodies the balance between *creative control* and *system-level power.*  
It stands as a bridge between two worlds — media creation and system mastery.  

> “Where tools are not just made to work — they are made to empower.”  
> — **Danx Exodus | Founder, Macan Angkasa**

---

## 🧠 Part of the Macan Angkasa Ecosystem  

| Suite | Description |
|--------|--------------|
| 🧠 **Macan AI Suite** | Artificial intelligence framework and natural language utilities |
| 🎨 **Macan Image Suite** | Professional-grade image editing and visual processing tools |
| 🧮 **Macan Productivity Suite** | Modern office and calculation tools |
| 🎬 **Macan Media Suite** | Core media framework and playback systems |
| ⚡ **Macan Fusion Suite** | Integration of multimedia and system-level utilities |

---

## 📜 License  
Licensed under the **MIT License**


MIT License
Copyright (c) 2025 Danx Exodus
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

## 🌐 Project Information  
**Author:** Danx Exodus  
**Organization:** Macan Angkasa — Independent Software Ecosystem  
**Type:** Multimedia & System Utility Suite  
**License:** MIT  
**Status:** Actively Maintained  

> *Innovation through fusion — a testament to independent engineering.*

---

## ⚖️ License Clarification Notice  
### Macan Super Video — Based on MPC-HC Open Source Components  

This software, **Macan Super Video**, is an independently developed application built as part of the **Macan Angkasa Ecosystem**, and is based in part on components derived from the **Media Player Classic – Home Cinema (MPC-HC)** project.

---

### 🧩 License Statement  
Portions of this software are derived from the MPC-HC project,  
which is distributed under the terms of the **GNU General Public License (GPL)**.  

As required by the GPL, any modifications made to the MPC-HC source code remain under the GPL license and retain the original copyright notice of the MPC-HC developers.

The proprietary modules, user interface elements, and ecosystem integration systems developed specifically for **Macan Super Video** are *independent works* authored by **Danx Exodus**,  
and are distributed under the **Macan Angkasa Binary License (MABL)**.

---

### 📜 License Structure Overview  

| Component | License | Ownership |
|------------|----------|-----------|
| MPC-HC Core Engine (base source) | GPL | MPC-HC Open Source Project |
| Macan Super Video UI Layer | MABL (Closed) | Danx Exodus |
| Macan Engine Integration | MABL (Closed) | Danx Exodus |
| Theming, Branding, and UX Assets | MABL (Closed) | Danx Exodus |

---

### ⚙️ Binary Distribution Policy  
This build of **Macan Super Video** is provided as a **binary-only release** under the Macan Angkasa Binary License (MABL).  
The application integrates open-source components from MPC-HC under compliance with the GPL license,  
and no modifications of the GPL components are distributed publicly without their corresponding source.

This ensures:
- Legal compliance with the GPL base code,  
- Protection of proprietary modules and internal APIs,  
- Consistent user experience within the Macan Angkasa software ecosystem.

---

### 📎 Attribution  
The original MPC-HC project and its contributors retain full copyright of the MPC-HC source code.  
All rights to proprietary modules, additional code, and the **Macan Angkasa** branding remain with **Danx Exodus**.  

Official MPC-HC repository:  
🔗 [https://github.com/mpc-hc/mpc-hc](https://github.com/mpc-hc/mpc-hc)

---

**Danx Exodus — Founder & Lead Developer**  
**Macan Angkasa Ecosystem**  
> “Built on open foundations. Refined through independent innovation.”


