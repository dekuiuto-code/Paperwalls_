<div align="center">

# 🖼️ Paperwalls (SANKOU! Walls)

**A high-performance, open-source wallpaper curation engine, lossless image viewer, and desktop styling hub.**

Inspired by Japanese design reference portals (*Sankou*) and *unixporn* desktop aesthetics. Built to serve uncompressed, pristine visuals directly to creators, developers, and customization enthusiasts.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Release-v1.0.0-emerald)](https://github.com/dekuiuto-code/Paperwalls_/releases)
[![Framework](https://img.shields.io/badge/UI-aniui-violet)](https://github.com/dekuiuto-code)
[![API](https://img.shields.io/badge/API-Free%20%26%20Public-brightgreen)](#-free-public-api)

---

</div>

## ✨ Key Features & Capabilities

### 🎨 Visual & Curation Engine
* 🖼️ **8,000+ Curated Wallpapers**: Directly indexes community-driven, high-resolution artwork cataloged from open-source repositories.
* 💎 **Lossless Image Quality**: Delivers uncompressed, full-fidelity visuals without aggressive stock image compression or intrusive watermarks.
* 📁 **Categorized Sets & Aesthetics**: Includes organized collections spanning *Set 1: Walls*, *Set 2: Aesthetic*, *Anime*, *Nature*, and *Digital Art*.
* 🔍 **Granular Filtering**: Filter artworks by phone aspect ratios, visual themes, aesthetic styling, and popularity metrics.

### 💻 User Experience & Local Storage
* 🌗 **Adaptive Dark & Light Themes**: Full UI support for dynamic dark and light mode switching.
* 🔖 **Zero-Account Bookmarking**: Save your favorite wallpapers directly into local browser storage for instant access anytime.
* 📦 **One-Click Batch Downloads**: Export your entire personal saved collection in a single compressed `.ZIP` file.
* 🎬 **Motion & Animation Control**: Dedicated landing screen motion toggles to play or pause background landing animations.

### 📑 Deep Image Metadata
* 🎨 **Dominant Color Extraction**: View exact HEX color codes for each wallpaper to match desktop/mobile themes.
* 📐 **Technical Specifications**: Inspect full resolution dimensions, file formats, and aspect ratio details.
* ✍️ **Creator Attribution**: Built-in credits acknowledging authors and open-source contributors.

---

## 🌐 Free Public API

We offer a **100% Free Public API** for developers, theme creators, and app builders to query and fetch wallpaper metadata, categories, and direct full-resolution image links directly into their own applications.

* ⚡ **Free & Open Access**: No API keys or authentication required to fetch wallpaper index data.
* 📊 **Metadata Rich**: Access JSON responses containing HEX color palettes, exact dimensions, tags, and creator credits.
* 🚀 **High Performance**: Lightweight endpoints structured for instant response times and fast image caching.

---

## ⚙️ Tech Stack & Architecture

* **UI Framework**: Powered by `aniui` components.
* **Storage Engine**: Client-side IndexedDB / LocalStorage caching for fast response times.
* **Image Delivery**: Caching layer designed for high-resolution photo loading without quality degradation.
* **Responsive Layout**: Tailored viewports optimized for mobile, tablet, and desktop environments.

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Node.js (v18+) and npm/pnpm installed on your machine.

### Installation

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/dekuiuto-code/Paperwalls_.git](https://github.com/dekuiuto-code/Paperwalls_.git)
   cd Paperwalls_
   
