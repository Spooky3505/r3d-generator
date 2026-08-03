# R3D Generator

Browser-based tool that converts AutoCAD DXF geometry and load takeoffs into a
**RISA-3D (`.r3d`) model file**. No install, no build step, no dependencies.

**Live: https://spooky3505.github.io/r3d-generator/**

Everything runs locally in your browser — no file you drop on the page is ever
uploaded anywhere.

## Use it

1. Open the live site (or download `index.html` and open it directly).
2. Drop any combination of: HSS geometry DXF, Pin BC DXF, matched-load CSV,
   notional-load CSV.
3. **Generate R3D File**, review the summary, **Download**.

A second panel, **Combine Load Files**, merges multiple per-structure load
exports (`.xlsx`, tab-delimited `.xls`, `.csv`) into one combined workbook.

## About this repository

This repo holds the built page only — a single self-contained HTML file with all
CSS and JavaScript inline. It is published from source that is developed
privately elsewhere; open an issue here rather than sending a pull request.
