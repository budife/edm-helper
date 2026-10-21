# eDM Helper - Daftar Tools dan Fungsi

## Overview
eDM Helper is a collection of useful tools for email marketing and everyday productivity. All tools are free and easy to use.

---

## 📚 Daftar Tools

### 1. **Bookmarklet** 
- **File:** `bookmarklet.html`
- **Icon:** 📖
- **Purpose:** Browser tools for quick actions and shortcuts
- **Fitur:**
  - Drag-and-drop bookmarklets for instant productivity
  - Tools that run directly in the browser
  - Tidak perlu instalasi tambahan

### 2. **Campaign Counter**
- **File:** `campaign-counter.html`
- **Icon:** 📈
- **Fungsi:** Mengelola nomor Campaign ID dari export Monday secara lokal
- **Fitur:**
  - Import XLSX langsung di browser
  - Merge / Replace modes for XLSX data
  - Ringkasan campaign, ID unik, reblast, dan baris gagal
  - Tab Regular hingga 9000 Series
  - Campaign names, blast dates, and reblast details in click popups
  - Export JSON sebagai backup lokal
  - Penyimpanan IndexedDB lokal dan Reset Local Data
  - Bookmarklet Monday memiliki database lokal terpisah

### 3. **Config eDM**
- **File:** `config.html`
- **Icon:** ⚙️
- **Fungsi:** Konfigurasi dan manage email marketing settings
- **Fitur:**
  - Advanced options
  - Template configuration
  - SMTP settings
  - Custom parameters

### 4. **Database Checker**
- **File:** `database-checker.html`
- **Icon:** 🗄️
- **Fungsi:** Validasi package database secara lokal dan uji URL layout publik secara opsional
- **Fitur:**
  - Validasi package database lokal
  - Uji URL layout publik (opsional, via CORS proxy)
  - Status loading / empty / error yang jelas

### 5. **Database Generator**
- **File:** `database-generator.html`
- **Icon:** 🧬
- **Fungsi:** Generate file output database campaign dari input customer dan KRHRED secara lokal
- **Fitur:**
  - Output empat file campaign
  - Bulk paste customer + KRHRED
  - Custom field mapping
  - Processing 100% lokal di browser

### 6. **WFH Tracker**
- **File:** `wfh-tracker.html`
- **Icon:** 📅
- **Fungsi:** Track dan manage work from home days
- **Fitur:**
  - Calendar integration
  - Daily logging
  - Summary reports
  - Export timesheet

### 7. **Layout Checker**
- **File:** `layout-checker.html`
- **Icon:** 📏
- **Fungsi:** Cek kompatibilitas layout email
- **Fitur:**
  - Cross-email client testing
  - Device compatibility check
  - Responsive design testing
  - Screenshot comparison (html2canvas)

### 8. **Layout Slicer**
- **File:** `layout-slicer.html`
- **Icon:** ✂️
- **Fungsi:** Copy folder campaign dan slice layout PDF/gambar menjadi aset gambar berurutan
- **Fitur:**
  - Slice PDF (pdf.js) dan gambar
  - Drag line untuk menentukan potongan
  - Export via File System Access API
  - Template-aware campaign renaming

### 9. **DOCX to HTML**
- **File:** `doc-to-html.html`
- **Icon:** 📄
- **Fungsi:** Convert file DOCX menjadi HTML siap upload langsung di browser
- **Fitur:**
  - Convert DOCX ke HTML (Mammoth)
  - Editor CodeMirror
  - Zip hasil (JSZip)
  - 100% client-side

### 10. **TNC Uploader**
- **File:** `tnc-uploader.html`
- **Icon:** 📎
- **Fungsi:** Rename, queue, simpan, dan generate public link untuk PDF terms & conditions secara lokal
- **Fitur:**
  - Rename + queue PDF
  - Generate public link
  - Tidak upload PDF ke server

### 11. **Text Correction**
- **File:** `text-correction.html`
- **Icon:** 🔤
- **Fungsi:** Convert teks yang di-paste menjadi plain text dan terapkan transformasi teks umum secara lokal
- **Fitur:**
  - Strip formatting
  - Transformasi teks umum
  - Processing lokal

---

## 🛠️ Fitur Utama Platform

### Performance Optimized
- Flat design for optimal performance on low-spec laptops
- No heavy animations
- CSS minimalis dan efisien

### Design System
- Warna tema: Merah (#F18C8E) dan Putih
- Clean, modern flat design
- Responsive across devices

### Accessibility
- Semua tools memiliki proper ARIA labels
- Keyboard navigation support
- Screen reader friendly

---

## 📁 Struktur File

```text
eDM-Helper/
├── index.html                 # App shell (sidebar + route container)
├── 404.html                   # GitHub Pages SPA fallback
├── content/                  # Markdown content rendered per route
├── docs/                     # Documentation content
├── css/                      # Shared tokens + per-tool styles
├── js/                       # App shell, per-tool scripts, utilities
├── tools/                    # Standalone tool pages (embedded by routes)
├── vendor/                   # Locally mirrored third-party assets
├── scripts/                  # Maintenance/release helpers
├── tests/                    # Node test suite
├── server.py                 # Local dev server (python server.py)
└── package.json              # Test script + CI config
```

---

## 🔧 Technologies Used

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Icons:** Font Awesome 6.5.2
- **Design:** Custom CSS with flat design principles
- **Performance:** Optimized for low-spec devices

---

## 💡 Tips Penggunaan

1. **Bookmarklet** - Drag bookmarklets to the browser toolbar for quick access
2. **Campaign Counter** - Import Monday XLSX files to review used numbers and the next ID
4. **Layout Checker** - Test layouts across email clients for compatibility

---

## 🚀 Cara Menggunakan

1. Buka `index.html` di browser
2. Click the desired tool
3. Follow instruksi di setiap halaman
4. Semua data tersimpan locally (tidak ada server)

---

## 📝 Catatan

- Semua tools berjalan client-side (tidak perlu internet)
- Data aman karena tidak terupload ke server
- Dapat digunakan offline setelah di-download
- Free forever, no hidden costs

---

*Last Updated: 2025*
