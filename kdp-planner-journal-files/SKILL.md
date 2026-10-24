---
name: kdp-planner-journal-files
description: Rules for building and delivering Amazon KDP interiors and cover wraps (planners, journals, low-content books).
---

# KDP planner & journal files

## Delivery
- Browser PDF export from inside apps can be unreliable for large files. Deliver KDP files as self-contained HTML (fonts and images inlined) in a `kdp-files/` folder.
- Give these print steps every time: open in Chrome → Ctrl/Cmd+P → Save as PDF → paper Letter (or the cover's own size) → margins None → scale Default → Background graphics on.
- Split interiors into parts of ~100 pages (one HTML file per part). Tell the user to merge them in order with any PDF merge tool and check the final page count.

## Interior
- 8.5 × 11 in trim unless told otherwise. Black & white.
- Design pages at 612 × 792 px and zoom 1.3333 onto the page via the page width/height.
- Keep writing areas white (no solid black boxes people need to write in).
- KDP limits for 8.5 × 11 B&W paperback: min 24 pages, max 828.

## Cover wrap
- Width = 0.25 in bleed + 2 × trim width + spine. Height = trim height + 0.25 in.
- Spine = pages × 0.002252 in (white paper) or × 0.0025 in (cream).
- Always match the spine to the exact final interior page count. KDP rejects the cover if the size doesn't match the uploaded interior.
- Keep the barcode area clear: 2 × 1.2 in, lower right of the back cover, 0.25 in from trim.

## Low-content rules
- Planners and journals are low-content: paperback or hardcover only. No Kindle eBook.
- No free KDP ISBN for low-content: publish without one or use your own.
