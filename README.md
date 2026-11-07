# Thai Exam Camera Assistant v2

## Deploy to GitHub Pages
1. Extract this ZIP.
2. Upload **all contents** of this folder to the root of your GitHub Pages repository (or preserve the folder structure).
3. Enable GitHub Pages in repository Settings → Pages.
4. Open the HTTPS GitHub Pages URL on your phone.

## Features
- New app icon and branded mobile header
- Favicon and iPhone home-screen icon
- PWA manifest and install prompt (supported browsers)
- Service worker caches the app shell and icon files
- Existing PDF import/OCR, camera capture, question OCR, and document-grounded AI answer flow

## Important
- Camera access requires HTTPS or localhost.
- PDF.js and Tesseract.js are loaded from CDNs; initial use requires internet.
- AI analysis requires an OpenAI API key and internet. The key is entered in the page and is not stored in local storage.
- Do not publish a file containing a real API key. This bundle contains no API key.
- The service worker caches the app shell, not the AI service or the PDF you select.
