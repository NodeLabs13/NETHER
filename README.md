# Nether ESP32 Firmware (Trial Edition)

**Advanced Penetration Testing Firmware for ESP32**  
*Inspired by Picoshot & ESP32 Deauther Projects*

---

## DISCLAIMER

**This firmware is for EDUCATIONAL and AUTHORIZED SECURITY TESTING purposes only.**

The authors of this software are not responsible for any misuse, damage, or illegal acts caused by this program.  
- Do not use this tool on networks you do not own or have written permission to test.  
- Using this tool against unauthorized networks is illegal and punishable by law.  
- By downloading and using this firmware, you agree to take full responsibility for your actions.

---

## Trial vs Full Version

This is the **Trial Edition** of Nether Firmware. It allows you to test the core stability and functionality before upgrading.

### Trial Edition
-   ✅ **WiFi Deauther**: Active
-   ⚠️ **Evil Twin**: Limited (15 Uses)
-   ❌ **Beacon Spam**: Locked
-   ❌ **BLE Spam**: Locked
-   ❌ **Payload Injection**: Locked

### Full Version
-   ✅ **WiFi Deauther**: Included
-   ✅ **Evil Twin**: **UNLIMITED**
-   ✅ **Beacon Spam**: Included
-   ✅ **BLE Spam**: Included
-   ✅ **Payload Injection**: Included

---

## Activation & Support

To activate your device MAC address for the **Full Version** or get technical support, please join our official Telegram group:

👉 **[Join Telegram Group](https://t.me/+jSIUaVgwVipjNzll)**

---

## Antivirus Notice

> **⚠️ IMPORTANT: Matikan Antivirus / Windows Defender terlebih dahulu sebelum menjalankan Flash Tool.**

File `Nether Flash Tool.exe` mungkin terdeteksi sebagai virus oleh beberapa antivirus. **Ini adalah False Positive** (deteksi palsu) yang umum terjadi pada semua aplikasi yang dikompilasi dari Python.

Aplikasi ini **AMAN** dan **TIDAK mengandung malware**. Deteksi terjadi karena:
-   Aplikasi menggunakan teknik enkripsi internal untuk melindungi lisensi.
-   Aplikasi mengakses port serial (USB) untuk flashing firmware ke ESP32.
-   Pola ini mirip dengan perilaku malware menurut heuristic antivirus, padahal sebenarnya bukan.

**Cara menonaktifkan Windows Defender sementara:**
1.  Buka **Windows Security** → **Virus & threat protection**.
2.  Klik **Manage settings** di bawah "Virus & threat protection settings".
3.  Matikan **Real-time protection**.
4.  Jalankan Flash Tool, lalu aktifkan kembali setelah selesai.

> Anda juga bisa menambahkan folder ini ke **Exclusion List** agar tidak perlu mematikan antivirus setiap kali.

---

## Installation Guide

This package comes with the **Nether Flash Tool (Secure Edition)** to make installation easy.

1.  **Matikan Antivirus**: Nonaktifkan Windows Defender / antivirus lainnya (lihat bagian di atas).
2.  **Connect ESP32**: Plug your ESP32 board into your computer via USB.
3.  **Open Flash Tool**: Run `Nether Flash Tool.exe` found in this folder.
4.  **Activate Trial License**:
    -   Klik **"Read MAC"** untuk membaca MAC Address perangkat ESP32 Anda.
    -   Tool akan secara otomatis mendaftarkan MAC Address dan mengaktifkan lisensi **Trial**.
    -   Pastikan status lisensi berubah menjadi **"Trial"** sebelum melanjutkan.
5.  **Flash Firmware**:
    -   Pindah ke menu **"Flash"**.
    -   Pilih file firmware yang disediakan jika tidak terdeteksi otomatis.
    -   Klik **"Start Flashing"** dan tunggu hingga selesai.
6.  **Connect to AP**:
    -   Network: **"NETHER"**
    -   Password: `superadmin`
7.  **Access Dashboard**:
    -   Open browser: `http://1.1.1.1/`

---

## Gallery

### Themes
| | |
|:---:|:---:|
| ![Modern Theme](Screenshot/Modern%20Theme.jpg) <br> **Modern Theme** | ![Arcade Theme](Screenshot/Arcade%20Theme.jpg) <br> **Arcade Theme** |
| ![Theme Settings](Screenshot/Theme%20Settings.jpg) <br> **Theme Customization** | ![General UI](Screenshot/Screenshot%20(60).png) <br> **Dashboard** |

### Captive Portal Templates
| | | |
|:---:|:---:|:---:|
| ![Modern Clean](Screenshot/Modern%20Clean%20UI%20Template.png) <br> Modern Clean | ![Windows 11](Screenshot/Windows%2011%20UI%20Template.png) <br> Windows 11 | ![Android](Screenshot/Android%20UI%20Template.png) <br> Android |
| ![Wi-Fi Login](Screenshot/Wifi%20UI%20Template.png) <br> Wi-Fi Login | ![Security Check](Screenshot/Secure%20UI%20Template.png) <br> Security Check | ![Router Update](Screenshot/IP%20UI%20Template.png) <br> Router Update |

---

## ❤️ Credits & Appreciation

Special thanks to:

-   **Picoshot**: Massive inspiration for the initial concept and functionality. Thank you for paving the way!
-   **ESP32 Deauther (Spacehuhn)**: The pioneer of ESP8266/ESP32 WiFi auditing tools.
-   **NimBLE-Arduino**: incredible BLE library.

