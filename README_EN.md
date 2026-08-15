<div align="center">

# 🚀 Xray Config Converter | Cloudflare Worker Bypass & Upload Speed Fixer

[![زبان](https://img.shields.io/badge/Language-%D9%81%D8%A7%D8%B1%D8%B3%DB%8C-green?style=for-the-badge)](README.md)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Xray Core](https://img.shields.io/badge/Xray--Core->=26.6.27-orange?style=for-the-badge)](https://github.com/XTLS/Xray-core)

<p align="center">
  <b>A fully client-side web utility that converts VLESS and Trojan subscription links into custom Xray JSON configurations with TLS Fragment settings, bypassing Cloudflare domain restrictions and resolving upload speed throttling.</b>
</p>

[📌 Live Demo](https://seyedng.github.io/Fragment_Fingerprint_Converter/) • [Technical Details on Patterniha Telegram channel](https://t.me/patt_channel_x/91?single)

</div>

---

## ⚡ Key Features

* 🔒 **100% Client-Side Processing:** All parsing, transformation, and generation occur entirely inside your browser. No sensitive configuration data is ever sent to external servers.
* 🧩 **Advanced TLS Fragment Engine:** Applies customized TLS Hello fragmentation and frame splitting to effectively bypass deep packet inspection (DPI) and SNI blocks.
* 🚀 **Upload Speed Optimization:** Tunes transport layer parameters according to modern Xray-core strategies to fix upload throttling on worker endpoints.
* 🔄 **Smart Subscription Fetcher:** Features multi-fallback CORS proxy integration to seamlessly pull and decode base64 subscription endpoints directly from the UI.
* 🇮🇷 **Custom Traffic Routing:** Toggleable routing rules for bypassing domestic Iranian traffic (`.ir` domains / IPs) and blocking advertising networks.
* 📥 **Standardized `ff.txt` Export:** Direct download/copy support formatted specifically for modern GUI clients like v2rayNG and NekoBox.

---

## 📋 Prerequisites

To ensure proper parsing of the generated JSON output, verify that your client app uses updated core binaries:

| Dependency | Minimum Required Version |
| :--- | :--- |
| **Xray-Core** | `>= 26.6.27` |
| **v2rayNG** | `>= 2.2.6` |

---

## 🛠️ Usage Guide

1. Open `index_en.html` in any web browser or access the live deployment.
2. Paste your raw `vless://` or `trojan://` URI links (or fetch via subscription URL / `.txt` file upload).
3. Customize your output routing rules (Ad-blocking / Iranian site bypass).
4. Click **Convert Configs**, then copy the result or download the generated **`ff.txt`** file.

---

<div align="center">

**Woman, Life, Freedom**

Crafted with ❤️ by [SeyedNG](https://github.com/SeyedNG) | [Telegram Channel](https://t.me/SeyedNG)

</div>
