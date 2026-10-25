# 🦉 OEncode

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCipher-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **OEncode** — CTF Encode / Decode Chain Engine ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OEncode is a CLI encode/decode chain engine for CTF and forensics work. It auto-detects nested encodings, recursively unwraps layers, and supports a wide codec set including Base58/64/32/85, hex, URL/HTML, classical ciphers, JWT, and compressed Base64 blends. Distinct from OConvertX’s GUI suite—focused on scriptable pipelines.

---

## ✨ Features

- Encode and decode with named codecs (base64, base58, hex, URL, HTML, and more)
- Auto-detect mode with recursive unwrap of nested layers
- XOR/Caesar brute helpers for simple classical obfuscation
- JWT, Quoted-Printable, Punycode, Morse, ROT, and Gzip+B64 support
- File or text input with JSON output for scripting
- ANSI colour toggle for clean log capture

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OEncode -t 'SGVsbG8=' --decode base64
./OEncode -t 'payload' --encode hex --json
./OEncode -f sample.txt --auto
./OEncode --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
