# HyCare Referral Form App

Single-file HTML application for filling the HyCare NDIS Referral Form PDF.

## Features
- Dynamically generated form from embedded schema
- Text fields, checkboxes, funding table
- **Signatures** (Participant + Referrer): draw with mouse/touch/stylus, or upload an image (white background removed automatically); placed on the signature lines of the generated PDF
- **PDF Preview** (embed + open in new tab)
- Generate and download filled PDF
- Dark mode support
- Fully client-side (uses pdf-lib)

## Usage
1. Open `index.html` in a browser
2. Fill the form
3. Draw or upload signatures if needed
4. Use **Preview** or **Generate filled PDF**

The updated `index.html` includes signature drawing and preview. Due to the embedded PDF size, the full file may need to be uploaded manually if the automated push was truncated.

## File
- `index.html` — the complete app
