# UI Components Design Sample

A lightweight static demo page that showcases reusable UI components, layout patterns, and theme behavior using plain HTML and CSS.

## Features

- Form patterns for common inputs (`text`, `select`, `textarea`, `checkbox`, radio toggle groups).
- Reusable button styles (primary and secondary).
- Field headers with action groups.
- Status pills (`inactive`, `active`, `error`).
- Log panel variants (neutral, success, failure).
- Modal dialog examples for success and failure states.
- Theme support for:
  - system preference (`prefers-color-scheme`)
  - manual override via `body[data-theme='light' | 'dark']`

## Project Structure

- `public/index.html` – demo markup for all UI components.
- `public/style.css` – component styling, design tokens, and theme variables.

## Getting Started

No build step is required.

### Option 1: Open directly

Open `public/index.html` in your browser.

### Option 2: Run a local static server

```bash
python3 -m http.server 8000 --directory public
```

Then visit:

- <http://localhost:8000>

## Purpose

This repository is intended as a design reference and starter template for quickly prototyping interface sections with consistent visual styles.

## License

This project is licensed under the MIT License. See `LICENSE` for details.
