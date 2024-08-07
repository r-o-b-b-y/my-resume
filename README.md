# Single HTML File Resume

A build-less, easily shareable resume written in markdown and parsed using the marked JavaScript library. Styled with a GitHub markdown stylesheet for a familiar look.

## Features

- **Markdown-Based**: Written in markdown for easy readability and editing.
- **JavaScript Parsing**: Uses the marked JavaScript library to parse markdown.
- **Graceful Degradation**: Displays plain text markdown if JavaScript is disabled.
- **Export Options**:
  - **HTML**: Export to HTML where JavaScript is no longer needed.
  - **PDF**: Export to PDF using a button/link that triggers the browser's print feature.
- **Cleanup**: Removes any DOM or script elements with the class `cleansup` during export.
- **Easily Sharable**: Can be shared as a plain HTML file or PDF, making resume uploading and emailing straightforward.
- **GitHub Markdown Styling**: Styled with a GitHub markdown stylesheet for a familiar and clean look.

## Usage

### Development Server

To serve the resume for development purposes, use a static file server:

- Using `npx serve`:
  ```sh
  npx serve
  ```
  
  