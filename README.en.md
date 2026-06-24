<p align="left">
  <a href="README.md"><img src="https://img.shields.io/badge/中文-中文版-red?style=for-the-badge" alt="中文"></a>
  <a href="README.en.md"><img src="https://img.shields.io/badge/English-Current-blue?style=for-the-badge" alt="English"></a>
  <a href="README.ja.md"><img src="https://img.shields.io/badge/日本語-Japanese-green?style=for-the-badge" alt="日本語"></a>
</p>

<p align="center">
  <img src="social-preview.png" alt="PDF Forge - PDF Toolbox in Browser" width="800">
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/FranciscoLaurent/pdf-forge?style=social" alt="Stars">
  <img src="https://img.shields.io/github/forks/FranciscoLaurent/pdf-forge?style=social" alt="Forks">
  <img src="https://img.shields.io/github/license/FranciscoLaurent/pdf-forge" alt="License">
  <img src="https://img.shields.io/github/repo-size/FranciscoLaurent/pdf-forge" alt="Size">
</p>

# PDF Forge — Local PDF Editor Built with 3-Prompt AI Conversation

> 🚀 **From concept to product in just 3 AI conversation rounds: core features → single-file packaging → UI polish. 100% Vibe Coding, zero handwritten code.**

A fully local PDF editing tool that runs entirely in your browser. **A single HTML file** — no server, no installation, no file uploads. All processing happens locally on your machine.

Featuring an elegant Anthropic brand-style design with comprehensive PDF page editing operations.

![PDF Forge Demo](demo.gif)

---

## ✨ Core Features

### Page Operations
- 📂 **Open PDF**: Support multiple PDF files simultaneously, or drag & drop files into the interface
- 🗑️ **Delete Pages**: One-click deletion with multi-select batch support
- ➕ **Insert Pages**: Insert pages from other PDFs at any position (before/after/start/end)
- 🔀 **Drag & Reorder**: Visual drag-and-drop to reorder pages, with multi-page drag support
- 🔄 **Rotate Pages**: 90° rotation with real-time thumbnail updates
- 📋 **Duplicate Pages**: Duplicate selected pages right after the originals
- 📤 **Extract Pages**: Export selected pages as a separate PDF
- ↔️ **Reverse Order**: Reverse the order of selected pages
- 💾 **Export PDF**: Merge all pages and generate the final PDF

### Interaction Features
- ⌨️ Complete keyboard shortcut support
- 🖱️ Thumbnail zoom control (50%-200%)
- 📁 Resizable sidebar
- 📊 Real-time statistics (total pages / selected / file count)
- 🔔 Toast notifications for operation results
- 🎨 Elegant Anthropic brand-style UI with paper texture

---

## 🚀 Usage

### Direct Use
1. Download the `pdf-forge.html` file to your computer
2. Double-click to open it in your browser (Chrome/Edge/Firefox recommended)
3. First open requires internet to load PDF.js and PDF-lib dependencies (via CDN), then it works offline

### Share with Others
Just send the `pdf-forge.html` file to anyone. They double-click to use it — no installation required.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| Click page | Select single page |
| `Shift + Click` | Select range of pages |
| `Delete` / `Backspace` | Delete selected pages |
| `Ctrl + A` | Select all / deselect all |
| `Ctrl + S` | Export PDF |
| `Esc` | Deselect / close dialog |
| Drag page | Reorder pages |

---

## 🛠️ Tech Stack
- **PDF Rendering**: [PDF.js](https://mozilla.github.io/pdf.js/)
- **PDF Processing**: [PDF-lib](https://pdf-lib.js.org/)
- **Pure Frontend**: HTML + CSS + Vanilla JavaScript, no framework dependencies
- **Single File**: All code inlined in one HTML file, under 60KB

---

## 🎯 The 3-Prompt AI Conversation Process

This project was 100% generated through AI conversations, taking just **3 prompts** with zero handwritten code, in under 15 minutes total:

### 🟢 Round 1: Build Complete Features from Scratch
**Prompt:** "Develop a local PDF editor with comprehensive features. For example, delete a page from a PDF file, insert pages from another PDF into a PDF, etc. Visual drag-and-drop is preferred."
- Time: 6 min 3 sec
- Completed all core features: open, delete, insert, drag-reorder, rotate, duplicate, extract, export
![Round 1: Building the Local PDF Editor](1.png)

### 🟡 Round 2: Single-File Packaging for Easy Sharing
**Prompt:** "Can this app be implemented with just a single HTML file? I need to forward it to more people."
- Time: 4 min 7 sec
- Inlined all HTML/CSS/JS into one file, zero dependencies, ready to use
![Round 2: Merging into Single HTML File](2.png)

### 🔴 Round 3: Production-Grade UI Polish
**Prompt:** "Make the interface more beautiful, using Anthropic brand style."
- Time: 4 min 43 sec
- Complete UI redesign: Anthropic brand color system, typography, paper texture, motion details — production-quality visuals
![Round 3: Anthropic Brand-Style UI](3.png)

---

## 📦 Sample Files

The `sample-pdfs/` directory contains two test PDFs you can drag into the app:
- `sample-report.pdf` - 4-page annual business report
- `sample-manual.pdf` - 3-page user manual

---

## 🔒 Privacy
All PDF processing happens entirely in your browser. **Files are never uploaded to any server.**

---

## 📄 License
[MIT License](LICENSE)
