# JDRP Report

Report Designer & Viewer Berbasis Browser

[![Version](https://img.shields.io/badge/version-v1.0-green)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()

JDRP Report adalah report designer dan viewer berbasis browser — drag & drop, data binding dinamis, dan export ke PDF, Excel, Word dalam satu platform.

## Fitur Utama

### Visual Designer
Drag & drop elemen langsung ke canvas dengan fitur:
- Resize elemen
- Snap ke grid
- Multi-select
- Undo/redo penuh

### Data Binding Dinamis
Koneksikan field langsung ke data source JSON dengan:
- Expression engine untuk kalkulasi
- Format otomatis
- Grouping data

### CrossTab Report
Buat laporan pivot otomatis dengan:
- Group header & footer
- Subtotal per kelompok data

### Chart Interaktif
Integrasi Chart.js dengan 6 tipe chart:
- Bar, Line, Pie, Doughnut, Radar, Polar
- Data dinamis dari source

### Peta Interaktif
Tampilkan data geografis dengan jsVectorMap:
- World, Indonesia, USA, dan 10+ region lainnya
- Region click untuk URL
- Tooltip dengan hint

### Barcode & QR Code
30+ tipe barcode via bwip-js:
- CODE128, QR, EAN-13, UPC, PDF417, DataMatrix
- Render ke Canvas
- Export PNG

### Import JasperReports
Import file .jrxml JasperReports langsung ke JDRP:
- Konversi otomatis elemen
- Band dan expression
- Auto-convert ke format native

## 12 Tipe Elemen

1. **Teks & Field** — Label statis atau field dinamis dengan expression
2. **Tabel** — Header + data rows dari source atau statis
3. **Chart** — 6 tipe (bar, line, pie, doughnut, radar, polar)
4. **Barcode** — 30+ tipe
5. **Peta** — jsVectorMap (World, Indonesia, USA, +10)
6. **Gambar** — URL atau base64, resize proporsional
7. **Shape** — 40+ bentuk (flowchart, basic, arrows, callout)
8. **Garis & Kotak** — Separator dan pembatas dekoratif

## Multi-format Export

Semua elemen (barcode, chart, map, shape) dirender sebagai gambar PNG nyata di setiap format:

| Format | Deskripsi |
|--------|-----------|
| **.pdf** | Multi-halaman dengan html2pdf, render per chunk untuk data besar |
| **.xlsx** | ExcelJS native dengan embedded image, cell styling, freeze header |
| **.docx** | docx.js native dengan ImageRun, table support |
| **Cetak** | Print langsung dari browser via iframe |

## Cara Kerja

1. **Rancang Layout** — Buka designer, drag elemen ke canvas, atur band header-detail-footer
2. **Bind Data** — Hubungkan field ke data source JSON, tulis expression
3. **Preview Live** — Viewer merender laporan real-time, navigasi halaman, zoom, filter
4. **Export & Cetak** — Pilih format PDF, Excel, Word, atau cetak langsung

## Teknologi

- **bwip-js** — Barcode generator (30+ symbology)
- **Chart.js** — Chart interaktif
- **jsVectorMap** — SVG map engine
- **ExcelJS** — Export Excel native
- **docx.js** — Export Word native
- **html2pdf.js** — Export PDF

## Stats

- 12+ Tipe elemen
- 4 Format export
- 30+ Tipe barcode

## Demo

[Lihat Demo](demo/report-designer.html)

## Lisensi

MIT License

## Author

Jimmy Andrian Davius — Perancang dan pengembang JDRP Report
