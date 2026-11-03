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

## Portable reading saves and outlines

Choose **Save reading + notes** to download a `.txt` data file containing extracted reading text, the next word position, typed notes, vector handwriting, and reading settings. It contains no PDF, app HTML, or executable code. Choose **Open saved / text file** to restore it. Save another copy after changes; downloaded files do not update automatically. Saves can be moved between devices and hosting addresses. Full saves are limited to 20 MB. Ordinary plain text can also be opened as reading text.

Use **Save notes text** and **Open notes text** for separate notes-only text files (up to 5 MB on import). The notes editor supports plain text, dot bullets and five outline levels: I., A., 1., a., i. Enter continues a list; Enter on an empty item exits it. Indent and Outdent switch outline levels.
