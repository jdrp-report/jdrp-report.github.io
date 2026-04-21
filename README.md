# JDRP Report

Browser-based Report Designer & Viewer

[![Version](https://img.shields.io/badge/version-v1.0-green)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()

JDRP Report is a browser-based report designer and viewer — drag & drop, dynamic data binding, and export to PDF, Excel, Word all in one platform.

## Key Features

### Visual Designer
Drag & drop elements directly onto canvas with:
- Element resize
- Snap to grid
- Multi-select
- Full undo/redo

### Dynamic Data Binding
Connect fields directly to JSON data source with:
- Expression engine for calculations
- Automatic formatting
- Data grouping

### CrossTab Report
Create automatic pivot reports with:
- Group header & footer
- Subtotals per data group

### Interactive Chart
Chart.js integration with 6 chart types:
- Bar, Line, Pie, Doughnut, Radar, Polar
- Dynamic data from source

### Interactive Map
Display geographic data with jsVectorMap:
- World, Indonesia, USA, and 10+ more regions
- Region click for URL
- Tooltip with hint

### Barcode & QR Code
30+ barcode types via bwip-js:
- CODE128, QR, EAN-13, UPC, PDF417, DataMatrix
- Render to Canvas
- Export PNG

### Import JasperReports
Import .jrxml JasperReports files directly into JDRP:
- Auto-convert elements
- Band and expression
- Auto-convert to native format

## 12 Element Types

1. **Text & Field** — Static label or dynamic field with expression
2. **Table** — Header + data rows from source or static
3. **Chart** — 6 types (bar, line, pie, doughnut, radar, polar)
4. **Barcode** — 30+ types
5. **Map** — jsVectorMap (World, Indonesia, USA, +10)
6. **Image** — URL or base64, proportional resize
7. **Shape** — 40+ shapes (flowchart, basic, arrows, callout)
8. **Line & Box** — Decorative separators and borders

## Multi-format Export

All elements (barcode, chart, map, shape) are rendered as real PNG images in every export format:

| Format | Description |
|--------|-------------|
| **.pdf** | Multi-page with html2pdf, chunk rendering for large data |
| **.xlsx** | ExcelJS native with embedded image, cell styling, freeze header |
| **.docx** | docx.js native with ImageRun, table support |
| **Print** | Print directly from browser via iframe |

## How It Works

1. **Design Layout** — Open designer, drag elements to canvas, arrange band header-detail-footer
2. **Bind Data** — Connect fields to JSON data source, write expressions
3. **Live Preview** — Viewer renders reports in real-time, navigate pages, zoom, filter
4. **Export & Print** — Choose PDF, Excel, Word, or print directly

## Technology

- **bwip-js** — Barcode generator (30+ symbology)
- **Chart.js** — Interactive chart
- **jsVectorMap** — SVG map engine
- **ExcelJS** — Native Excel export
- **docx.js** — Native Word export
- **html2pdf.js** — PDF export

## Stats

- 12+ Element types
- 4 Export formats
- 30+ Barcode types

## Demo

[View Demo](demo/report-designer.html)

## Contact

Reach me via email: [davius02@gmail.com](mailto:davius02@gmail.com)

## License

MIT License

## Author

Jimmy Andrian Davius — Designer and developer of JDRP Report