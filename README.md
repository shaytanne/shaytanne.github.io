# Shay Tanne - Personal Portfolio & CV

Repo for my personal website and portfolio, hosted on GitHub Pages: [shaytanne.github.io](https://shaytanne.github.io).

## Tech Stack
- **Engine:** [Jekyll](https://jekyllrb.com/) (GitHub Pages standard)
- **Diagrams:** [Mermaid.js](https://mermaid.js.org/)
- **Icons:** [Font Awesome 6](https://fontawesome.com/)

## Project Structure
```text
.
├── _config.yml         # Site configuration, metadata, and plugin settings
├── _layouts/           # Jekyll HTML layouts
│   ├── default.html    # Main layout with responsive sidebar and navigation
│   └── page.html       # Alternative single-column container layout
├── assets/
│   ├── css/
│   │   └── styles.css  # Stylesheet with responsive design
│   ├── docs/
│   │   └── cv_sep26.pdf # Latest CV (PDF)
│   └── images/         # Photos and visual assets
├── cv.md               # Interactive CV / Resume page (/cv/)
├── index.md            # Homepage and personal bio (/)
├── research.md         # Research projects and publications (/research/)
├── .gitignore          # Git ignore rules for Jekyll build artifacts
└── Gemfile             # Ruby dependencies for local Jekyll preview
```

## Running Locally

> **Note:** GitHub Pages automatically builds and deploys your site whenever you push to `main`—installing Ruby/Jekyll locally is **optional** and only needed if you want an offline preview.

### 1. Prerequisites (Ubuntu / Debian)
If you don't already have Ruby and Bundler installed:
```bash
sudo apt update
sudo apt install ruby-full build-essential zlib1g-dev
gem install bundler
```

### 2. Install Dependencies & Serve
```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000` in your browser.
