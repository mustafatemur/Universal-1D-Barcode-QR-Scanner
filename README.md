# 📷 Universal 1D Barcode + QR Scanner (Single Page)

A lightweight, single-page web application for scanning **1D barcodes** and **QR codes** directly from your browser using the **Chrome Barcode Detection API** (with automatic ZXing fallback for unsupported browsers).  
Includes **scan history**, **CSV export**, and the ability to **scan from image files**.

---

## 🚀 Features

- **BarcodeDetector API** first, **ZXing** fallback.
- Supports common formats:  
  QR, CODE128, CODE39, EAN-13, EAN-8, UPC-A, UPC-E, ITF, Codabar, CODE93.
- **Stop on Scan** and **Beep sound** options.
- **Local scan history** stored in `localStorage`.
- **CSV export** for scan history.
- Scan **live from camera** or **from image file upload**.
- **HTTPS or localhost** required for camera access.

---

## 📦 Installation

1. Download the HTML file from this repository.
2. Serve it locally or open via HTTPS:  
   - Local: `http://localhost` (e.g., using `Live Server` in VS Code)  
   - Or upload to a secure server with HTTPS enabled.

---

## 🖥️ Usage

1. **Open the page** in Chrome (or any browser with BarcodeDetector API support).
2. **Select desired formats** from the checkbox list.
3. Click **Start (Back Camera)** to begin scanning.
4. **Scan History** will list all scanned results with timestamps.
5. **Export to CSV** or **Clear History** anytime.
6. Use **Scan from Image** to upload and scan codes from files.

---

## 🔒 Permissions

- The application requests **camera access** to perform live scans.
- No data is sent to any server — all processing happens locally in your browser.

---

## 🛠️ Technologies

- **JavaScript (Vanilla)**
- **HTML5**
- [Chrome Barcode Detection API](https://developer.mozilla.org/en-US/docs/Web/API/Barcode_Detection_API)
- [ZXing](https://github.com/zxing-js/library) (fallback)

---

## 📄 License

MIT License — You are free to use, modify, and distribute this software.

---

### 💡 Tip:
For the best experience, use **Google Chrome** or any Chromium-based browser with BarcodeDetector enabled.
