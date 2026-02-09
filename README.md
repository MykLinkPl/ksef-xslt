# ksef-xslt (FA(3)) — HTML/PDF rendering for KSeF invoices

Fork of `asoio/ksef-xslt` with small practical improvements for day-to-day use.

This repository contains an **XSLT stylesheet** that transforms **KSeF FA(3) XML invoices** into a clean, printable **HTML layout** (suitable for PDF export).



## Changelog (fork changes)

### 2026-02-xx
- Removed external Google Fonts URLs (`fonts.googleapis.com`) and switched to local system fonts (eg. Segoe UI / Arial).
  - Reason: headless Chromium/Edge PDF printing can intermittently render **blank text** if web fonts are not loaded in time.
  - Using system fonts makes PDF generation deterministic and avoids dependency on internet access / proxies / blocked external requests.

## License

Same license as upstream project.
