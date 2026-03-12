# Project: GR2026 Gemeenteraadsverkiezingen Presentation

Dutch-language Reveal.js presentation about the Amsterdam municipal elections on 18 March 2026.

## Type

Reveal.js presentation

## Local Preview

Start a local server and preview in Chrome:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080/index.html` in the browser.
Navigate to a specific slide with hash: `http://localhost:8080/index.html#/4` (0-indexed).

## Style Guide

This project uses the shared CFG presentation design system. See `C:\Users\Sambo\Dropbox\Coding\_shared\style-guide.md` for the full reference.

Key points:
- Fonts: Playfair Display (headings), Plus Jakarta Sans (body)
- Slide size: 1280x720, 4% margin
- Theme: Light (Reveal.js `white.css`)
- Colours: see CSS variables in style guide
- Header brand: `<strong>GR2026</strong> <em>&middot; Gemeenteraad</em>`

## Project-Specific Notes

- 14 slides covering how municipal elections work + Amsterdam-specific issues
- Tone: casual, friendly, explaining basics for friends with no assumed political knowledge
- Two custom CSS classes: `.gov-diagram` (government structure flowchart) and `.pipeline` (election flow)
- All diagrams are CSS-only (no Mermaid or external libraries)
