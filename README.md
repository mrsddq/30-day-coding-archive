# 30-Day Coding Archive

A 30-day coding and revision archive containing DSA notes, HTML/CSS projects, JavaScript practice, React coursework, and a chat app.

## Structure

```text
DSA/
HTML-CSS-Completed-Project/
Javascript/
React-JS-Course/
chatapp/
```

## Status

Baseline repository structure is complete as a learning archive:

- categorized course folders
- frontend practice projects
- DSA notes and revision material
- placeholder HTML content replaced in visible practice pages
- root README
- root `.gitignore`

## Portfolio Position

Keep this archived. It shows learning history, not a focused product or research project.

Use [docs/LEARNING_INDEX.md](docs/LEARNING_INDEX.md) to navigate the useful parts and decide what should be extracted later.

## Run a static exercise

No root npm install or build is required. For example:

```bash
python -m http.server 8000 --bind 127.0.0.1 --directory "HTML-CSS-Completed-Project"
```

Open http://127.0.0.1:8000/ and select a project. These are static exercises; the commerce pages do not provide checkout, authentication, or persistence. `chatapp/` contains package metadata only and is not a runnable chat service. The two React HTML files are empty placeholders, so they are not runnable React applications.

## Portability and provenance

The React lesson directory is now `React-JS-Course/React/`; the earlier trailing space has been removed so it can be checked out on Windows. Course documents and existing credits are preserved. This repository records learning and should not be represented as a collection of original production applications. Historical notes may reference the old directory name.
