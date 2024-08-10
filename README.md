# My Resume is a...
# ✨ Resilient Single File Resume Creator ✨ 

## demo: [https://rbbydotdev.github.io/resume/](https://rbbydotdev.github.io/resume/)

## ✍️ ➡️ 📄 👀 👍

### Just edit the html then open it in your browser, IT'S EASY AND SIMPLE!

A build-less, easily shareable resume written in markdown and parsed using the marked JavaScript library. Styled with a GitHub markdown styles. Export to single file dependency-less HTML document or PDF for easy uploading and emailing.

 _A Low-Tech Resume for a High-Tech World_

**No build commands or servers required. Just open the `index.html` file in a browser and read your resume. Click the "Export to HTML" or "Export to PDF" buttons to save a compact and self-contained copy for uploading or emailing.**

## Features
- Mobile Friendly!
- **Single File HTML Export**: Exports to a javascript-less single file with zero dependencies, css is inserted inline, even images are not externally linked but base64 encoded and embedded.
- **Markdown-Based**: Written in markdown for easy readability and editing.
- **JavaScript Parsing**: Uses the marked JavaScript library to parse markdown.
- **Graceful Degradation**: Prototype displays plain text markdown if JavaScript is disabled, once exported to html no javascript is needed
- **Export Options**:
  - **HTML**: Export to compact self-contained HTML file where JavaScript is no longer needed.
  - **PDF**: Exports to PDF easily via printing to PDF
- **Easily Sharable**: Can be shared as a plain HTML file or PDF, making resume uploading and emailing straightforward.
- **GitHub Markdown Styling**: Styled with a GitHub markdown stylesheet, simple accessible familar styles

## Usage

- Just open it your favorite ide to edit it and in a browser to preview it
- Click Export to HTML or Export to PDF to save a compact and self contained copy for uploading or emailing.
- Don't forget to set the `<title>` tag, this is used to create the filename when exporting

## Motivation

The motivation behind this project is to ensure that the resume content is always accessible and easy to manage:

- **Resilient Design**: designed to be resilient, the progenitor version will even display plain text markdown if JavaScript is disabled, ensuring the content is always readable. (but when exporting to HTML this does not happen)
- **Single File Simplicity**: The entire resume is contained within a single HTML file, making it easy to download, edit, and share without any build steps.
- **Flexible Export Options**: Developers can simply download the file, edit it, and then choose to share it as-is, or export it to HTML or PDF for easy uploading or emailing.
- **No Build Steps Required**: The project is build-less, meaning there are no complex build steps or dependencies. Just download, edit, and share.
- **Markdown Readability**: The original markdown format is human-readable, making it easy to edit and transfer to other formats.
