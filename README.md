# Atharv Sandeep Patil - Portfolio

Static portfolio website for Atharv Sandeep Patil, built with plain HTML, CSS, and a small amount of JavaScript for the light/dark theme toggle.

## Overview

This portfolio highlights my work across Java, Python, AWS, and RAG-powered applications. It is designed as a recruiter-friendly single-page website with sections for education, skills, experience, projects, research, credentials, creative work, and contact links.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- GitHub Pages for hosting

## Project Structure

```text
.
├── index.html
├── styles.css
├── Atharv_Sandeep_Patil_Resume.pdf
├── images/
│   ├── logo.png
│   ├── IMG_3707_upright.jpg
│   └── creative-side.png
└── prototype/
    └── porfolio-v2-prototype.html
```

## Local Preview

Open `index.html` directly in a browser, or run a small local server from the repository root:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## GitHub Pages Deployment

This site is ready to host with GitHub Pages because the production entry file is at the repository root:

```text
index.html
```

In GitHub:

1. Go to repository `Settings`.
2. Open `Pages`.
3. Set source to `Deploy from a branch`.
4. Select the `main` branch.
5. Select `/ (root)` as the folder.
6. Save.

The site will be published at:

```text
https://atharvp18.github.io/portfolio-v2/
```

## Notes

- `prototype/` contains the design prototype used before creating the production static files.
- The live site should use the root `index.html` and `styles.css`.
- Resume downloads use `Atharv_Sandeep_Patil_Resume.pdf` from the repository root.
