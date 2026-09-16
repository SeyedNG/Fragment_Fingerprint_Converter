<div align="center">

# 🚀 Xray Config Converter | Cloudflare Worker Bypass & Upload Speed Fixer

[![زبان](https://img.shields.io/badge/Language-%D9%81%D8%A7%D8%B1%D8%B3%DB%8C-green?style=for-the-badge)](README.md)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Xray Core](https://img.shields.io/badge/Xray--Core->=26.6.27-orange?style=for-the-badge)](https://github.com/XTLS/Xray-core)

<p align="center">
  <b>A fully client-side web tool that converts VLESS and Trojan links into fragmented, Cloudflare-friendly configs — bypassing worker/CDN restrictions and fixing upload speed throttling.</b>
</p>

[📌 Live Demo](https://seyedng.github.io/Fragment_Fingerprint_Converter/) • [Technical details on the Patterniha Telegram channel](https://t.me/patt_channel_x/91?single)

</div>

---

## ⚡ Key Features

* 🔒 **100% Client-Side:** All parsing and conversion happen in your browser — nothing is sent to any server.
* 🧩 **TLS Fragment Engine:** Splits the TLS Hello into fragments to bypass DPI and SNI-based blocking.
* 🚀 **Upload Speed Fix:** Tunes transport settings to resolve upload throttling on Cloudflare Worker endpoints.
* 🔄 **Subscription Fetcher:** Pulls and decodes base64 subscription links directly in the browser, with a multi-source fallback for when one proxy is blocked or slow.
* 📁 **Multiple Input Methods:** Paste links directly, upload a `.txt` file, or fetch a subscription URL — all can be combined before converting.
* 🇮🇷 **Optional Routing Rules:** Toggle ad-blocking and bypass for Iranian (`.ir`) sites and IPs.
* 🌐 **IP Randomization:** Optionally replace each config's server address with one from your own IP pool.
* 📤 **Two Output Formats:**
  * **Normal** — plain `vless://` / `trojan://` links for the [PattN](https://github.com/patterniha/PattN/releases/latest) / [PattNG](https://github.com/patterniha/PattNG/releases/latest) clients.
  * **Custom (JSON)** — full Xray configs, downloadable as one `ff.txt` file or as separate JSON files in a ZIP (for clients like v2rayN that require one config per file).
* 🏷️ **Remarks Preserved:** Each config keeps its original name/remark — nothing is renamed during conversion.

---

## 📋 Prerequisites

To make sure the generated configs work correctly, keep your client up to date:

| Dependency | Minimum Version |
| :--- | :--- |
| **Xray-Core** | `>= 26.6.27` |
| **v2rayNG** | `>= 2.2.6` |

---

## 🛠️ Usage Guide

1. Open `index_en.html` in your browser, or use the [live demo](https://seyedng.github.io/Fragment_Fingerprint_Converter/).
2. Paste your `vless://` / `trojan://` links, fetch them from a subscription URL, or upload a `.txt` file.
3. Choose an output format (Normal or Custom JSON) and set your routing / IP options.
4. Click **Convert Configs**, then copy the output or download it (`ff.txt`, or the separate-ZIP option for Custom JSON).

---

<div align="center">

**Woman, Life, Freedom**

Crafted with ❤️ by [SeyedNG](https://github.com/SeyedNG) | [Telegram Channel](https://t.me/SeyedNG)

</div>
