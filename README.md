# Kaizen District — Feasibility Study

Interactive feasibility study page by Kaizen District for Urban Development. The project name is entered on the page.

Every assumption from the Excel workbook is an editable input. Areas, construction costs, sales, net profit, the group / Kaizen profit split, the break-even residential price and a ±10% sensitivity analysis update live. A quarterly cash-flow model (editable payment durations and payment plans) gives NPV, IRR, peak funding and payback. The model reproduces the workbook formulas exactly (net project profit EGP 2,451,003,516 at the original values).

Saved studies and versions are kept in the browser (localStorage) and can be exported/imported as a JSON file to move between devices. The "إصدار نسخة PDF" button builds a paginated A4 PDF with the company logo, project name and version in each page header and page numbers in the footer (libraries load from cdnjs/jsDelivr on first use).

Single self-contained file: `index.html` (no build step, no dependencies besides Google Fonts).

## Live page

https://hassanien13-afk.github.io/KAIZEN-DISTRICT/

Hosted with GitHub Pages from the `main` branch root. To update the page, replace `index.html` in this repository; Pages republishes it within about a minute.
