# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is Chengjie Liu's personal academic website hosted on GitHub Pages:
- **URL**: https://cjliu-nju.github.io/CjLiu-NJU.github.io/
- **Branch**: `main` (automatically deployed to GitHub Pages)

## Architecture

This is a **static HTML website** with no build system or framework:
- **Single source of truth**: `index.html` contains all HTML, CSS, and JavaScript
- **Assets**: All images are in the root directory
- **No dependencies**: No npm, Ruby, or Python packages required
- **No CI/CD**: Deployment happens automatically when pushing to `main`

## Key Files

- **`index.html`**: The entire website (26KB) - contains all content, styling, and scripts
  - Sections: Biography, News, Publications, Awards, Teaching
  - Responsive design with mobile breakpoints
  - Uses Leaflet library for mapping (CDN-hosted)

## Development

To work on this website:
1. Edit `index.html` directly
2. Open `index.html` in a browser to preview changes
3. Commit and push to `main` to deploy

There are no build, test, or lint commands - it's just static HTML.
