# Huma’s Speed Reader

A browser app for iPhone, iPad, and desktop. Import a PDF or paste text, start at the cursor, and read 1–8 words at a time at an adjustable words-per-minute rate. Includes continuous lined notes with typing, optional bullets, and handwriting with PNG export.

## Use

Serve `index.html` from a static web host. No build, package installation, or server application is required. For GitHub Pages, publish the repository's default branch from the root folder using Settings → Pages.

1. Import a PDF with selectable text, or paste text.
2. Place the cursor in the reading text and choose **Read from cursor** to skip introductory pages.
3. Choose a reading speed and adjust **Words at a time** from 1 to 8.
4. Use Start/Pause to resume, Back 10 to move back, and Restart to begin again.

PDF extraction loads PDF.js from cdnjs and requires internet. Image-only PDFs need OCR, which is not included. Selected PDFs are processed in your browser; the app has no upload backend. Reading text and position reset on reload. Typed notes and handwriting save in this browser’s local storage when available; they do not sync between devices or hosting addresses. Export notes with Save text or Save PNG for a backup.

On iPhone, open the hosted app in Safari and choose Share → Add to Home Screen.

## Source

This repository contains the app source. The separate ChatGPT Sites deployment does not automatically update when this repository changes.
