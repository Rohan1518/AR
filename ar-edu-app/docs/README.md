AR Edu App
=========

An Augmented Reality educational web app with an AI-like chatbot and quiz mode. It overlays 3D models using A-Frame + AR.js and loads topic data from JSON files.

Quick Start
-----------

1) Install deps:

```bash
npm install
```

2) Run a static server (recommended):

```bash
npm run dev
```

3) Open the app at http://localhost:5173 and allow camera access.

Features
--------

- Chatbot: Ask questions; it responds and can trigger a related 3D AR model
- AR Viewer: View and inspect 3D objects with markers
- Quiz Mode: Get quick quizzes based on your last topic

Build
-----

```bash
npm run build
```

This bundles JS/CSS and copies assets to `build/`.

