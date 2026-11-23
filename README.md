# Inner Practice — Laser Focus Companion

Mobile-first GitHub Pages web app for the supplied **Laser Focus · All 12 Resources** PDF.

## Included
- 135 revision cards based on text extracted from the 45-page PDF. Each card has a source page reference. Hindi and English wording is preserved where present in the source. The short question prompts and “Why it matters” explanations are study aids, not quotations.
- “Open in book” button on cards to jump to the cited PDF page (when the PDF is selected in Reader).
- Reader: select your own PDF on the device; local storage / IndexedDB, page navigation, zoom, bookmarks, and resource jump list. PDF is not included or hosted in this repository.
- Revision session limit defaults to 10; continue, shuffle, revisit, skip, and module filter.
- Editable action sheets for idea/why, values, goal, start/target dates, milestones, actions, tracking and reflection.
- Export/import revision deck and personal data backup.

## Deploy on GitHub Pages
Upload the contents of this folder to the repository root (or your Pages folder), enable Pages in Settings, and open the site. Select the PDF from your phone in Reader.

## Privacy and offline
The selected PDF and personal action-sheet data are stored locally in the browser on that device. The PDF is never sent to GitHub Pages. PDF.js loads from CDN on first use and may require an internet connection initially; the app shell is service-worker cached.

## Source mapping
Card text is extracted from the supplied 45-page PDF and includes PDF page numbers. Extraction can imperfectly read OCR/ligatures; verify important wording against the page in Reader.
