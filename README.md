# Lab Protocol Portfolio

A GitHub Pages + MkDocs site for organizing experimental protocols, workflows, and troubleshooting notes.

## 1. Install
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## 2. Run locally
```bash
mkdocs serve
```
Open `http://127.0.0.1:8000`

## 3. Build static site
```bash
mkdocs build
```

## 4. Deploy to GitHub Pages
Push this repository to GitHub, then enable GitHub Pages in repository settings or use the included GitHub Actions workflow.
