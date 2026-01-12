# 🔥 CLI-Esp32Marauder

Talk to your **ESP32Marauder** like a hacker from a movie 🎬  
No software. No drama. Just **Chrome + ESP32** 😎

---

## 🧰 Requirements (Simple Stuff)
- ✅ Any **ESP32 (4MB)** — *ESP32U recommended*
- 👉 https://robu.in/product/esp32-38pin-development-board-wifibluetooth-ultra-low-power-consumption-dual-core/
- 🃏 Micro SD Card Reader Module
- 👉 https://amzn.in/d/2sz5lXE
- 💻 Laptop / PC
- 🌐 Chrome Browser (Desktop ONLY)
- 🔌 USB Cable
- 🧠 Brain (optional but useful)

---

## ⚡ How to Flash ESP32 (Don’t Skip 😅)

Before using CLI, flash the firmware properly.

📘 Official Wiki (Read this once):  
👉 https://github.com/justcallmekoko/ESP32Marauder/wiki/update-firmware

---

### 📦 Download Required Files

| File | Flash Address | Link |
|----|----|----|
| Firmware | `0x10000` | [Download](https://github.com/justcallmekoko/ESP32Marauder/releases/download/v1.2.1/esp32_marauder_v1_2_1_20250207_v6.bin) |
| Bootloader | `0x1000` | [Download](https://github.com/justcallmekoko/ESP32Marauder/raw/master/FlashFiles/MarauderV4/esp32_marauder.ino.bootloader.bin) |
| Partitions | `0x8000` | [Download](https://github.com/justcallmekoko/ESP32Marauder/raw/master/FlashFiles/MarauderV4/esp32_marauder.ino.partitions.bin) |
| Boot App | `0xE000` | [Download](https://github.com/justcallmekoko/ESP32Marauder/raw/master/FlashFiles/FlipperZeroMultiBoardS3/boot_app0.bin) |

---

### 🌍 Web Flasher (Chrome Only)

Open this in **Chrome Desktop**:  
👉 https://esp.huhn.me/

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjEHxYB3OP_ucyOGpoRY0oR-Z2XMoZLVXFDRWTcEafRlmoNuXsKt-jHYaKCl5v32QhyrGcQolZ9_JE52dEnibuBK2JL8XAon6htzstgI1wEknYulXyQb9QLgSRA01opPf1tJt_9WtQEYFJkLnKA6Q5q2WrrLOmAcx1-exTRELFLVH8M__2LeRmvOKItMDJ_/s16000/4.png" width="700">
</p>

> Plug ESP32 → Select files → Flash → Relax ☕  

---
### 🃏 MicroSDCard Reader Module Connect to ESP32-WROOM-32

![WhatsApp Image 2026-01-12 at 5 01 14 PM](https://github.com/user-attachments/assets/04910eb8-fe54-4b9a-beef-f1eb320bdd59)


## 🖥️ Use the Web CLI

After flashing, open the CLI terminal:

👉 **CLI Terminal**  
🔗 https://webcli-esp32marauder.netlify.app/

<p align="center">
  <img src="https://github.com/user-attachments/assets/50b15624-a000-40b5-8a13-3098120755c0" width="700">
</p>

### Steps:
1. Open site in **Chrome Desktop**
2. Click **CONNECT**
3. Select ESP32
4. Type commands
5. Watch terminal talk back 😏

---

## 📱 Mobile Users (Read This or Cry Later 😭)

❌ Mobile browsers do NOT support Web Serial API
✔ UI + guides will open
❌ ESP32 connection will FAIL

👉 Use Chrome Desktop only

## ⚠️ Disclaimer (Important!)

This project is for EDUCATIONAL & INTERNAL use ONLY.

❌ No illegal usage
❌ No public attacks
❌ No WiFi drama

R0otpapa is NOT responsible if:

Your WiFi stops
Your ESP32 misbehaves
Your friend gets disconnected 😬

Use responsibly.

## ❤️ Credits & Links

🧠 ESP32Marauder by JustCallMeKoko
👉 https://github.com/justcallmekoko/ESP32Marauder

### 🧑‍💻 Web CLI & UI by R0otpapa

🔴 YouTube:
👉 https://youtu.be/MXmMG3ZiYYQ?si=dFbJ6h88LEuWFZeI

📸 Instagram:
👉 https://www.instagram.com/metarunsharma666/

<p align="center"> Made with ❤️, ☕ and late-night debugging <br> <b>— R0otpapa</b> </p>
