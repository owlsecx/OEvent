# 🔄 OEncode

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OForensics%20%2F%20Encoding-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-None%20(Standalone)-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OEncode** is a comprehensive encoder/decoder toolkit. It supports Base64 (standard, URL-safe, Base32, Base85), Hex, URL encoding, HTML entities, Binary, ROT ciphers, Morse code, Caesar cipher, auto-detection, and multi-layer chaining.

---

## 📌 Overview

OEncode is designed for quick encoding/decoding tasks, CTF challenges, and forensic analysis of encoded data. It includes 10 powerful modules with encode/decode/both modes and an intelligent auto-detect feature.

---

## 🖥️ Modules

| #  | Module               | Description |
|----|----------------------|-------------|
| **[1]** | **Base64**           | Standard / URL-safe / Base32 / Base85 |
| **[2]** | **Hex**              | Plain / 0x prefix / \x escape / xxd style |
| **[3]** | **URL**              | Standard / Full / Double encoding |
| **[4]** | **HTML**             | Named / Decimal / Hex entities |
| **[5]** | **Binary**           | Text ↔ Binary bits conversion |
| **[6]** | **ROT Cipher**       | ROT13 / ROT47 / Custom shift / Brute force |
| **[7]** | **Morse Code**       | Text ↔ Morse conversion + reference table |
| **[8]** | **Caesar Cipher**    | Encode / Decode / Brute force (1-25) |
| **[9]** | **Auto Detect**      | Automatically try all decoders |
| **[10]**| **Chain Encoder**    | Stack multiple encodings sequentially |

---

## 📊 Key Features

- **10 Encoding Schemes** — With full encode/decode support
- **Auto Detection** — Tries all decoders and highlights likely matches
- **Chain Encoder** — Apply multiple layers (e.g. Base64 → URL → ROT13)
- **Brute Force** — ROT and Caesar brute-force with all shifts
- **Morse Reference** — Built-in Morse code table
- **Rich Colored Output** — Clear labels for each transformation
- **Export Options** — Save results as JSON or TXT
- **Interactive Menu** — Clean and user-friendly interface

---

## ⚙️ Requirements

- **Linux or Windows**
- **No additional dependencies** — uses only Python standard library

---

## 🚀 Usage

```bash
./OEncode

📁 Output

Live Results — Color-coded encoded/decoded text with clear labels
Reference Tables — Morse code table available on demand
JSON Export — Structured results with input, mode, and all steps
TXT Export — Human-readable summary


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED TESTING & CTF USE ONLY
