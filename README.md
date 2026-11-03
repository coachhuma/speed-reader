# Speed Reader + Draw Pad

A browser app for iPhone, iPad, and desktop. Import a PDF or paste text, start at the cursor, and read 1–8 words at a time at an adjustable words-per-minute rate. Includes a drawing pad with PNG export.

## Use

Serve `index.html` from a static web host. No build, package installation, or server application is required. For GitHub Pages, publish the repository's default branch from the root folder using Settings → Pages.

1. Import a PDF with selectable text, or paste text.
2. Place the cursor in the reading text and choose **Read from cursor** to skip introductory pages.
3. Choose a reading speed and adjust **Words at a time** from 1 to 8.
4. Use Start/Pause to resume, Back 10 to move back, and Restart to begin again.

PDF extraction loads PDF.js from cdnjs and requires internet. Image-only PDFs need OCR, which is not included. Selected PDFs are processed in your browser; the app has no upload backend. Reloading the page resets the text, reading position, and drawing.

On iPhone, open the hosted app in Safari and choose Share → Add to Home Screen.

## Source

This repository contains the app source. The separate ChatGPT Sites deployment does not automatically update when this repository changes.
