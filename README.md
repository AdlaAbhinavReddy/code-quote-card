# Code Quote Card

A small, responsive quote card built with HTML, CSS, and Bootstrap 4 — a full-viewport background image with a centered, semi-transparent card displaying a quote in Bree Serif.

## Built With

- HTML5 & CSS3
- [Bootstrap 4.5.2](https://getbootstrap.com/docs/4.5/getting-started/introduction/) — flexbox utility classes
- [Google Fonts](https://fonts.google.com/) — Bree Serif
- jQuery & Popper.js — Bootstrap 4 JS dependencies

## Project Structure

```
quote-project/
├── index.html      # Page markup
├── style.css       # Custom styles
├── .gitignore      # Files Git should ignore
└── README.md       # Project documentation
```

## Getting Started

This is a static site — no build steps or installs needed.

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open `index.html` in your browser.

## Deploy with GitHub Pages (optional)

1. Push the code to GitHub (steps below).
2. In your repo, go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and `/ (root)` folder → **Save**.
4. Your site goes live at `https://<your-username>.github.io/<repo-name>/`.

## What Was Cleaned Up

- Renamed classes to describe what they are: `.bg` → `.page-background`, `.qute-text` → `.quote-card`.
- Merged the split `border` / `border-width` / `border-style` declarations into one shorthand line each.
- Quoted the `Bree Serif` font name and added a `serif` fallback.
- Removed `background-size` / `background-position` from `.quote-card` — it has no background image, only a color, so those properties had no effect.
- Added `<meta charset>`, `<meta viewport>`, and `<title>` for a valid, complete `<head>`.
- Moved `<script>` tags to the end of `<body>` so the page content loads first.

## Push to GitHub

```bash
cd quote-project

# Initialize a repo (skip if this folder is already one)
git init

# Stage and commit all files
git add .
git commit -m "Initial commit: Add quote card project"

# Make sure the default branch is named main
git branch -M main

# Link your GitHub repo (create an empty one on GitHub first, then paste its URL)
git remote add origin https://github.com/<your-username>/<repo-name>.git

# Push
git push -u origin main
```

Replace `<your-username>` and `<repo-name>` with your actual GitHub username and repository name.
