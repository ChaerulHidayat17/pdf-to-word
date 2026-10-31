# DocuMorph — Client-Side PDF to Word (.docx) Converter

> **100% Client-Side Privacy** · No Server Upload · Instant & Accurate Formatting

DocuMorph is a modern, privacy-first web utility to convert PDF documents into clean, fully-editable Microsoft Word (`.docx`) files directly in the user's browser. Built with **PDF.js**, **docx.js**, and styled with a crisp, minimal UI design.

🌐 **Live Demo:** [https://chaerulhidayat17.github.io/pdf-to-word/](https://chaerulhidayat17.github.io/pdf-to-word/)

---

## ✨ Key Capabilities

- **Zero Server Upload (100% Client-Side Privacy):** Your files never leave your device's memory. Safe for confidential reports, invoices, resumes, contracts, and academic papers.
- **True `.docx` File Structure:** Reconstructs genuine OpenXML Word formatting:
  - Font weights (Bold, Italic)
  - Auto-detected Headings (`Heading 2`)
  - Paragraph spacing and bullet lists
  - 1:1 Page Breaks
- **Interactive Document Workspace:**
  - Live canvas-rendered page thumbnail previews
  - Configurable conversion options (Page breaks, Auto-Headings, Custom filename)
  - Real-time animated progress bar with execution metrics
- **Lightweight & Blazing Fast:** Converts multi-page documents in seconds without server queues or rate limits.

---

## 🛠️ Tech Stack

- **Core Engine:** [PDF.js](https://mozilla.github.io/pdf.js/) (Layout & Text Extraction), [docx](https://docx.js.org/) (OpenXML Document Assembly)
- **Styling:** Tailwind CSS, Plus Jakarta Sans, JetBrains Mono
- **Deployment:** GitHub Pages / Vercel Static

---

## 🚀 Local Development

Simply open `index.html` in any modern web browser or serve it with Python:

```bash
python3 -m http.server 3000
```

Then visit `http://localhost:3000`.

---

Developed by **Chaerul Hidayat** ([Portfolio](https://chaerulhidayat17.github.io/portfolio/))
