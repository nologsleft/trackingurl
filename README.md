# Advanced Browser Fingerprinting & Data Exfiltration Framework

This project is a proof-of-concept browser-based fingerprinting and data collection tool disguised as a Cloudflare "Attention Required" page. It collects a wide range of system, network, and browser metadata from the client, including webcam snapshots, and sends the data to a configured Telegram bot.

---

## 🚀 Features

- Cloudflare-like fake session verification interface
- Detailed browser/system fingerprinting including:
  - Canvas fingerprint
  - WebGL fingerprint
  - Audio fingerprint
  - Installed fonts
  - Plugins and MIME types
  - Battery status
  - Device memory and core count
  - Network info (downlink, latency, save data)
  - Headless browser detection
  - WebRTC IP discovery
  - Geolocation (if granted)
  - Public IP address detection
  - LocalStorage & IndexedDB persistent ID tracking
  - Webcam snapshot (image capture)
- Data exfiltration via Telegram Bot API

---

## 📦 Files

- `index.html` — Full HTML + JS code for the fingerprinting interface
- Uses:
  - [CryptoJS](https://github.com/brix/crypto-js) for hashing
  - [Font Awesome](https://fontawesome.com/) for UI icons
  - `api.ipify.org` for IP detection
  - `Telegram Bot API` for real-time data exfiltration

---

## 🔧 Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/nologsleft/
  
