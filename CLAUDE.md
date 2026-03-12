# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

PromptSoar is a static marketing/landing site for the PromptSoar iOS app (a prompt saving and organizing tool). The site is hosted on GitHub Pages at promptsoar.com.

## Architecture

This is a plain HTML/CSS site with no build system, bundler, or JavaScript framework. Pages are standalone HTML files sharing a single stylesheet (`styles.css`). There is no build step, test suite, or linter configured.

- `index.html` — Landing page with app description and nav links
- `features.html`, `privacy.html`, `support.html` — Subpages (currently minimal HTML fragments, not full documents)
- `styles.css` — Shared styles
- `CNAME` — GitHub Pages custom domain config (`promptsoar.com`)

## Development

No build or install commands. Open HTML files directly in a browser or use any local static server (e.g., `python3 -m http.server`).

## Branching

- `main` — Production branch (deployed via GitHub Pages)
- `develop` — Development branch; PRs target `main`
