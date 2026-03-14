# AIMA Exercises Website (v7) — Jupyter Notebook Viewer

A custom-designed static landing page that serves as a table of contents for all AIMA (Artificial Intelligence: A Modern Approach) exercises, rendered as Jupyter Notebooks via nbviewer.

## What It Does

- Provides a visually polished table of contents organized by AIMA textbook parts (I–VII)
- Links each chapter's exercises to rendered Jupyter Notebooks via [nbviewer](https://nbviewer.jupyter.org/)
- Covers 27 chapters spanning search, logic, probability, learning, NLP, robotics, and more
- Includes a responsive hamburger navigation menu

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| 🌐 HTML/CSS | Static landing page |
| 🅱️ [Bootstrap](https://getbootstrap.com/) 3.3 | Responsive grid layout |
| 📓 [nbviewer](https://nbviewer.jupyter.org/) | Jupyter Notebook rendering |
| 🔤 [Google Fonts](https://fonts.google.com/) | Lato typeface |
| 🎨 Linea Icons | Custom icon font |

## Getting Started

Simply open `index.html` in a browser, or deploy to GitHub Pages.

```bash
git clone https://github.com/stabgan/aima-website-7.git
cd aima-website-7
open index.html
```

## Project Structure

```
├── index.html               # Main landing page with TOC
├── style.css                # Custom styles
├── icon-font.css            # Linea icon font styles
├── fonts/                   # Linea icon font files
├── notebooks/               # Jupyter notebooks (underscore naming)
└── Jupyter notebook/        # Jupyter notebooks (original naming)
```

## Chapters Covered

| Part | Topics |
|------|--------|
| I | Introduction, Intelligent Agents |
| II | Search, Advanced Search, Game Playing, CSP |
| III | Logic, FOL, Inference, Planning, Knowledge Representation |
| IV | Probability, Bayes Nets, DBN, Decision Theory, Complex Decisions |
| V | Concept Learning, ILP, Bayesian Learning, Reinforcement Learning |
| VI | NLP, Communication, Perception, Robotics |
| VII | Philosophy, Future of AI |

## ⚠️ Known Issues

- The `notebooks/` and `Jupyter notebook/` directories contain duplicate content with different naming conventions.
- nbviewer links depend on the external nbviewer.jupyter.org service remaining available.
- The `Jupyter notebook/` directory has numbered duplicates (e.g., `1. intro-exercise.ipynb` alongside `intro-exercises.ipynb`).
