# ksef-xslt FA(3) — XSLT to HTML/PDF for Polish KSeF e-Invoices

Fork of `asoio/ksef-xslt` with practical improvements for generating **HTML and PDF previews of KSeF FA(3) e-invoices (Poland)**.

This repository provides an **XSLT stylesheet** for transforming **KSeF FA(3) XML invoices** into a clean, print-friendly **HTML layout**, suitable for reliable **PDF generation** (including headless Chromium / Edge).

## Changelog (fork changes)

### 2026-02-xx
- Removed external Google Fonts URLs (`fonts.googleapis.com`) and switched to local system fonts (eg. Segoe UI / Arial).
  - Reason: headless Chromium/Edge PDF printing can intermittently render **blank text** if web fonts are not loaded in time.
  - Using system fonts makes PDF generation deterministic and avoids dependency on internet access, proxies, or blocked external resources.

## License

Same license as upstream project.
