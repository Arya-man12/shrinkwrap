# Shrinkwrap

A browser-based file converter and compressor. Everything runs client-side in a single self-contained HTML page: your files never leave your device.

## Tools

- **Images**: convert between PNG, JPG and WebP, with a quality slider, max width and ZIP export.
- **PDF**: PDF tools built on [pdf-lib](https://pdf-lib.js.org/), with previews drawn by [pdf.js](https://mozilla.github.io/pdf.js/).
  - **Edit pages**: every page of every PDF on one board. Remove, rotate and drag pages into order, combine pages from several PDFs, and save the result or just the pages you select.
  - **Page numbers**: added on save, in six positions, as `3`, `3 / 12` or `Page 3 of 12`, with a start number and an option to skip a cover page.
  - **Gap finder**: lists every blank page, page break that leaves white space, and big gap inside a page, with its length, and hatches the gaps on the page previews so unneeded breaks are easy to find.
  - **Word export clean-up**: finds blank pages for one-click removal, trims wide white margins, or pulls half-empty pages together. A PDF can't re-flow like a Word file, so the real fix for gaps is removing the extra page breaks in Word.
  - **Merge, split and compress** whole files.
- **Text, CSV and JSON**: conversions between common text formats.

Each tool shows before/after sizes per file, and the page supports light and dark mode and phone widths.

## Use it

Open `index.html` in a browser, or visit the hosted version at https://arya-man12.github.io/shrinkwrap/.
