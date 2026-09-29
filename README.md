<img width="507" height="453" alt="Screenshot 2026-09-28 172051" src="https://github.com/user-attachments/assets/8a354731-907d-4f22-9ac8-4ed98a789e5a" />
# Xbox 360 ISO to .XEX Converter

A standalone Windows desktop utility designed to extract Xbox 360 game disc images (`.iso`) directly into loose `.xex` folder structures ready for RGH/JTAG consoles and PC emulation via Xenia.

---

## ⚡ Features

* **Built-In Binary Engine:** Directly unpacks Xbox disc file systems natively without requiring third-party command-line utilities.
* **Format Support:** Full compatibility with standard GDF, XGD2 (e.g., *Halo 3*), and high-density XGD3 partition offsets.
* **Automatic Desktop Output:** Automatically structures and extracts files into an organized `_xex` directory straight to your Desktop.
* **Modern UI:** Built with custom rounded dark-mode cards, live file-by-file extraction labels, and progress tracking.
* **Thread-Safe Architecture:** Background worker threads prevent the window from freezing or showing "Not Responding" during multi-gigabyte extractions.
* **Integrated Update Checker:** Automatically queries GitHub Releases on startup to notify you when a newer version is available.

---

## 🚀 How to Install & Use

1. Go to the **[Releases](https://github.com/Retrozcube/Xbox360-ISO-Converter/releases)** tab on the right side of this page.
2. Download the latest compiled **`Xbox360_ISO_Converter.exe`**.
3. Double-click the `.exe` to launch the application (no installation, Python, or setup required).
4. Click **Browse ISO** and select your game disc image.
5. Click **Convert to .XEX**. Your extracted game folder containing `default.xex` will appear on your Desktop.

---

## 🎮 Deployment to Xbox 360

1. Take the generated `_xex` folder from your Desktop.
2. Transfer the folder onto a **FAT32-formatted USB drive** or directly to your console storage (`Hdd1:\Games\`) via FTP.
3. Launch the game from **Aurora**, **DashLaunch**, or **XeXMenu** by selecting `default.xex`.

---

## 🛠️ Author & Project

Developed by **Retrozcube**  
GitHub: [https://github.com/Retrozcube](https://github.com/Retrozcube)
