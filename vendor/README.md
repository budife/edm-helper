# vendor/

Locally mirrored third-party assets. These are vendored here so the tools
run without fetching libraries from a public CDN (cdnjs). Keeping them in
the repository means the app works offline and does not send asset requests
to external hosts while processing campaign data.

## Contents

- `codemirror/5.65.16/` - CodeMirror editor (DOCX to HTML)
- `font-awesome/6.5.2/` - Icon font, including `webfonts/`
- `html2canvas/1.4.1/` - Screenshot capture (Layout Checker)
- `jszip/3.10.1/` - ZIP packaging (DOCX to HTML)
- `mammoth/1.8.0/` - DOCX to HTML conversion
- `pdf.js/4.10.38/` - PDF rendering (`pdf.min.mjs` + `pdf.worker.min.mjs`, Layout Slicer)

## Updating

Replace the files above with the same versions from cdnjs, keeping the
folder layout identical so the relative `../vendor/...` references in
`tools/*.html` and `js/*.js` keep resolving. Only bump versions when a
security fix is available upstream.
