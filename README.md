# 🖼️ Text Extractor App

A lightweight OCR tool for Windows — extract text from any part of your screen with a simple hotkey.

---

## 🚀 Features
- 📝 Text OCR from screenshots
- 🖱️ Select any screen area
- 📋 Auto copies text to clipboard
- ⚙️ Runs standalone — no Python or setup required
- ⌨️ Hotkey: `Ctrl + Shift + T`
- Press enter

---

## 🖥️ How to Use
1. **Download** the `.exe` from [Releases](https://github.com/Sachmann07/Text-Extractor-App/releases)
2. Double-click to run it
3. Press `Ctrl + Shift + T`  
4. Select screen area → Text auto-copied to clipboard

---

## ⚙️ Requirements (Important)

This app requires **Microsoft Visual C++ Redistributable** to run.

If you see an error like:

"The ordinal could not be located in the dynamic link library"

Install this once:

👉 Download: https://aka.ms/vs/17/release/vc_redist.x64.exe  
(Visual C++ Redistributable 2015–2022)

After installing, restart your PC and run the app again.

---

## 🧠 Also Required

- Windows 10 / 11
- Tesseract OCR installed  
  Default path: `C:\Program Files\Tesseract-OCR\tesseract.exe`

Download Tesseract here:  
https://github.com/tesseract-ocr/tesseract/wiki

## 📦 Tech Stack
- Python
- [PyTesseract](https://github.com/madmaze/pytesseract)
- [Pillow](https://pillow.readthedocs.io/)
- [keyboard](https://github.com/boppreh/keyboard)
- Packaged with [PyInstaller](https://pyinstaller.org/)

---

## 📄 License
MIT – use freely, modify, share.
