# ACM Conference LaTeX Template 2.12 (Structured)

This repository provides a cleaned and modular version of the official [ACM Conference Proceedings Primary Article Template](https://www.overleaf.com/latex/templates/acm-conference-proceedings-primary-article-template/wbvnghjbzwpc), reorganized into a scalable folder structure for better readability and collaboration.

**Based on:**  
**ACM Primary Article Template – LaTeX version 2.12 (Published January 2, 2025)**

## Folder Structure
```bash
.
├── acm-instructions/             # Original usage notes and ACM PDF guide
│   ├── acm_usage_notes.tex
│   ├── acmguide.pdf
│   └── sample-base.bib

├── acm-template/                 # ACM class and style files (LaTeX v2.12, Jan 2025)
│   ├── acmart.cls
│   ├── *.bbx / *.cbx / *.dbx     # Citation and bibliography styles
│   ├── ACM-Reference-Format.bst  # BibTeX style
│   ├── README.txt
│   └── sample-*.tex              # Sample documents for reference

├── appendix/                     # Optional appendix content
├── figures/                      # Figure assets (PDF, PNG, etc.)
├── sections/                     # Modular paper sections (intro.tex, methods.tex, etc.)
├── tables/                       # Optional standalone tables

├── bibliography.bib              # BibTeX bibliography file
├── macros.tex                    # Custom macros and shorthand commands
├── main.tex                      # Main LaTeX entry point
├── preamble.tex                  # Package imports and formatting
├── README.md                     # Project overview and build instructions
```

