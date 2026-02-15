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

> **⚠️ IMPORTANT: Disable Antivirus / Windows Defender before running the Flash Tool.**

The `Nether Flash Tool.exe` file may be detected as a virus by some antivirus software. **This is a False Positive** (false alarm) common with applications compiled from Python.

This application is **SAFE** and **DOES NOT contain malware**. Detection occurs because:
-   The application uses internal encryption to protect its license logic.
-   The application accesses the serial port (USB) to flash firmware to the ESP32.
-   These patterns trigger antivirus heuristics, even though the behaviors are legitimate.

**How to temporarily disable Windows Defender:**
1.  Open **Windows Security** → **Virus & threat protection**.
2.  Click **Manage settings** under "Virus & threat protection settings".
3.  Turn off **Real-time protection**.
4.  Run the Flash Tool, then re-enable protection after you are done.

> You can also add this folder to the **Exclusion List** so you don't have to disable antivirus every time.

---

## Installation Guide

This package comes with the **Nether Flash Tool (Secure Edition)** to make installation easy.

1.  **Disable Antivirus**: Turn off Windows Defender / other antivirus (see section above).
2.  **Connect ESP32**: Plug your ESP32 board into your computer via USB.
3.  **Open Flash Tool**: Run `Nether Flash Tool.exe` found in this folder.
4.  **Activate Trial License**:
    -   Click **"Read MAC"** to read your ESP32 device's MAC Address.
    -   The tool will automatically register the MAC Address and activate the **Trial** license.
    -   Ensure the license status changes to **"Trial"** before proceeding.
5.  **Flash Firmware**:
    -   Switch to the **"Flash"** menu.
    -   Select the provided firmware files manually if not detected automatically.
    -   Click **"Start Flashing"** and wait for completion.
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

