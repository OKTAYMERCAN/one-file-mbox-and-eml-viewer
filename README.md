# 📧 One-File MBOX & EML Viewer

![License](https://img.shields.io/badge/license-GPLv3-blue.svg)
![Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen.svg)
![Platform](https://img.shields.io/badge/platform-Any%20Browser-darkred.svg)
![Size](https://img.shields.io/badge/size-~40%20KB-orange.svg)

A single HTML file that opens `.mbox` archives and `.eml` messages in your browser, like a real mail client. No server, no build step, no installation, no internet connection. Download one file, open it, done — and your mail never leaves your computer.

## 🚀 Key Features

* ✅ **Zero setup:** One HTML file, no dependencies, no web server. Works offline by double-clicking.
* ✅ **Both formats:** Opens `.mbox` archives (Gmail Takeout, Thunderbird, Apple Mail) and standalone `.eml` messages. Select several files at once and they merge into one list.
* ✅ **Full MIME parsing:** Multipart messages, base64 and quoted-printable decoding, embedded `cid:` images and downloadable attachments.
* ✅ **Correct characters:** UTF-8, Windows-1254, ISO-8859-9 and more, including encoded and raw 8-bit headers. Turkish characters stay intact.
* ✅ **Private by design:** Nothing is uploaded. Message bodies render inside a sandboxed iframe that cannot run scripts, and remote images — including tracking pixels — are blocked until you allow them.
* ✅ **Search and sort:** Filter by sender or subject; sort by date, sender or subject.
* ✅ **Three views:** Formatted HTML, plain text, or raw message source. Export any message as `.eml`.
* ✅ **True black theme:** Pure `#000000` for OLED screens, with automatic color adaptation for HTML mail.
* ✅ **Bilingual:** Turkish and English interface, selected automatically from your browser language.

## 💻 Usage

[!NOTE] There is nothing to install. The file runs entirely inside your browser.

1. Download `one-file-mbox-and-eml-viewer.html`
2. Open it in any modern browser (double-click is enough)
3. Choose a file, or drag one onto the page

Large archives are indexed in chunks with a progress bar. Files above roughly 500 MB may be slow, since the browser holds the whole archive in memory.

## 📸 Screenshots
<img width="2183" height="1278" alt="Screenshot_20260909_161847" src="https://github.com/user-attachments/assets/2f377574-57c5-4bc8-8ca1-f067e4219ce2" />

<img width="1969" height="1282" alt="Screenshot_20260909_161346" src="https://github.com/user-attachments/assets/f2d9f51b-c452-4176-9ad5-b0099c10f178" />

<img width="2036" height="1159" alt="Screenshot_20260909_161230" src="https://github.com/user-attachments/assets/68995fd5-529c-4c7b-be30-94c72b3ffb36" />



## 📄 License

Copyright (C) 2026 Oktay Mercan

This program is free software: you can redistribute it and/or modify it under the terms of the **GNU General Public License v3.0** or (at your option) any later version. See [LICENSE](LICENSE) for the full text.

If you modify and redistribute it, you must release your changes under the same license, keep the copyright notices, and state what you changed. See [CHANGELOG.md](CHANGELOG.md).

---
AI used.
