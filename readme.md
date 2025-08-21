# Source-cery ✨

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Source-cery is a single-file HTML tool for scientific writing. Originally conceived to verify citations in AI-generated summaries, it's an equally powerful companion for human writers needing instant context on their references. It works by fetching and displaying PubMed details on hover—no installation required.

---

## Key Features

- **Real-time Interactive Preview:** Paste your text and see an enhanced version instantly.
- **Multi-Format Parsing:** Recognizes `\cite{}`, `(PMID: ...)`, and `pmid12345` formats.
- **Rich Hover Tooltips:** See the abstract, authors, and journal info on mouseover.
- **Author-Year Tags:** Automatically adds `[Author Year]` prefixes for context.
- **Customizable UI:** Resizable panels, themes (light/dark), and adjustable font/tooltip sizes.
- **Zero Dependencies:** 100% Vanilla JS, CSS, and HTML in a single file.

## How to Use

1.  **Download:** Get the `source-cery.html` file. (or click <a href="https://chen42.github.io/SourceCery/">this link</a>)
2.  **Open:** Open it in any modern web browser.
3.  **Paste:** Add your text to the left panel and start writing.

## How It Works

- **Frontend:** Vanilla HTML, CSS (with variables for themes), and JavaScript.
- **Data:** Fetches publication data from the public NCBI E-utils API.
- **Performance:** API calls are debounced, batched, and cached for efficiency.

## Project Genesis

This tool was built from an original idea and a series of feature requests by me. The code was iteratively generated and refined by Google's Gemini 2.5Pro.

## License

This project is licensed under the **MIT License**.
