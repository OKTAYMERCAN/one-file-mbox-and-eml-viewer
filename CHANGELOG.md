# Changelog

All notable changes to this project are documented here.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and this project uses [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [1.0.0] - 2026-09-09

Initial release.

### Added

- Single-file `.mbox` viewer that runs in the browser with no server or installation
- Support for standalone `.eml` files, and for opening several files at once
- MIME parsing: multipart messages, base64 and quoted-printable decoding, embedded `cid:` images
- Character set decoding for UTF-8, Windows-1254, ISO-8859-9 and others, including RFC 2047 encoded headers
- Attachment listing and download, including RFC 2231 encoded filenames
- Export of a single message as `.eml`
- Search by sender or subject, and sorting by date, sender or subject
- Formatted, plain-text and raw source views
- HTML bodies rendered in a sandboxed iframe with remote images blocked by default
- True black theme for OLED screens, with optional color adaptation for HTML mail
- Turkish and English interface, chosen automatically from the browser language
- Keyboard navigation and drag-and-drop file loading

---

<!--
  Bu dosyaya, projeyi değiştiren herkes kendi satırını ekler.
  GPL-3.0'ın 5. maddesi, değiştirenin neyi ve ne zaman değiştirdiğini
  belirtmesini gerektirir; bu dosya o kaydı tutar.

  Örnek:

  ## [1.1.0] - 2026-11-02

  ### Added
  - Parsing of calendar invitations (.ics attachments) - Veli Demir

  ### Fixed
  - Attachment names with non-ASCII characters were truncated - Veli Demir
-->
