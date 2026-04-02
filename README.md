# 🔄 OEncode

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OForensics%20%2F%20Encoding-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-None%20(Standalone)-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OEncode** is a powerful encoder/decoder toolkit. It supports Base64 (standard, URL-safe, Base32, Base85), Hex, URL, HTML entities, Binary, ROT ciphers, Morse code, Caesar cipher, and multi-layer chaining with auto-detection.

---

## 📌 Overview

OEncode is designed for CTF challenges, forensic analysis, and quick encoding/decoding tasks. It includes 10 modules covering the most common encoding schemes used in security testing and malware analysis.

---

## 🖥️ Modules

| #  | Module               | Description |
|----|----------------------|-------------|
| **[1]** | **Base64**           | Standard / URL-safe / Base32 / Base85 |
| **[2]** | **Hex**              | Plain / 0x / \x escape / xxd style |
| **[3]** | **URL**              | Standard / Full / Double encoding |
| **[4]** | **HTML**             | Named / Decimal / Hex entities |
| **[5]** | **Binary**           | Text ↔ Bits conversion |
| **[6]** | **ROT Cipher**       | ROT13 / ROT47 / Custom shift / Brute |
| **[7]** | **Morse Code**       | Text ↔ Morse conversion |
| **[8]** | **Caesar Cipher**    | Encode / Decode / Brute force |
| **[9]** | **Auto Detect**      | Try all decoders automatically |
| **[10]**| **Chain Encoder**    | Stack multiple encodings sequentially |

---

## 📊 Key Features

- **Comprehensive Support** — 10+ encoding schemes with encode/decode/both modes
- **Auto Detection** — Automatically tries all decoders to identify unknown encodings
- **Chain Encoder** — Apply multiple layers (e.g. Base64 → URL → ROT13)
- **Brute Force** — ROT and Caesar brute-force (1-25 shifts)
- **Rich Output** — Color-coded results with clear labels
- **Export Options** — Save results as JSON or TXT
- **Interactive** — Clean menu-driven interface with help and reference tables

---

## ⚙️ Requirements

- **Linux or Windows**
- **No additional dependencies** — uses only Python standard library

---

## 🚀 Usage

```bash
./OEncode

📁 Output

Live Results — Color-coded encoded/decoded output with clear labels
Reference Tables — Morse code reference available on demand
JSON Export — Structured results with input, mode, and all transformations
TXT Export — Human-readable summary


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED TESTING & CTF USE ONLY
