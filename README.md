# Nether ESP32 Firmware (Trial Edition)

**Advanced Penetration Testing Firmware for ESP32**  
*Inspired by Picoshot & ESP32 Deauther Projects*

---

## ⚠️ DISCLAIMER

**This firmware is for EDUCATIONAL and AUTHORIZED SECURITY TESTING purposes only.**

The authors of this software are not responsible for any misuse, damage, or illegal acts caused by this program.  
- Do not use this tool on networks you do not own or have written permission to test.  
- Using this tool against unauthorized networks is illegal and punishable by law.  
- By downloading and using this firmware, you agree to take full responsibility for your actions.

---

## ⚡ Trial vs Full Version

This is the **Trial Edition** of Nether Firmware. It allows you to test the core stability and functionality before upgrading.

```mermaid
graph TD
    classDef trial fill:#ffebee,stroke:#c62828,stroke-width:2px,color:#c62828;
    classDef full fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px,color:#2e7d32;
    classDef neutral fill:#f5f5f5,stroke:#9e9e9e,stroke-width:1px,color:#616161;

    subgraph TRIAL [ "🌟 TRIAL EDITION" ]
        direction TB
        T1["✅ WiFi Deauther"]:::neutral
        T2["⚠️ Evil Twin (15 Uses)"]:::trial
        T3["❌ Beacon Spam (LOCKED)"]:::trial
        T4["❌ BLE Spam (LOCKED)"]:::trial
        T5["❌ Payload Injection (LOCKED)"]:::trial
    end

    subgraph FULL [ "🚀 FULL VERSION" ]
        direction TB
        F1["✅ WiFi Deauther"]:::full
        F2["✅ Evil Twin (UNLIMITED)"]:::full
        F3["✅ Beacon Spam"]:::full
        F4["✅ BLE Spam"]:::full
        F5["✅ Payload Injection"]:::full
    end
    
    style TRIAL fill:#ffffff,stroke:#333,stroke-width:2px
    style FULL fill:#ffffff,stroke:#333,stroke-width:2px
```

---

## 🔓 Activation & Support

To activate your device MAC address for the **Full Version** or get technical support, please join our official Telegram group:

👉 **[Join Telegram Group](https://t.me/+jSIUaVgwVipjNzll)**

---

## 📦 Installation Guide

This package comes with the **Nether Flash Tool (Secure Edition)** to make installation easy.

1.  **Connect ESP32**: Plug your ESP32 board into your computer via USB.
2.  **Open Flash Tool**: Run `Nether Flash Tool.exe` found in this folder.
3.  **Flash Firmware**:
    -   Select the provided firmware files manually if not detected.
    -   Click **"Start Flashing"**.
4.  **Connect to AP**:
    -   Network: **"Nether AP"**
    -   Password: `password123`
5.  **Access Dashboard**:
    -   Open browser: `http://192.168.4.1/`

---

## 📸 Gallery

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

Special thanks to the open-source community:

-   **Picoshot**: Massive inspiration for the initial concept and functionality. Thank you for paving the way!
-   **ESP32 Deauther (Spacehuhn)**: The pioneer of ESP8266/ESP32 WiFi auditing tools.
-   **NimBLE-Arduino**: incredible BLE library.

---

*Built with ❤️ by Nether Team*
