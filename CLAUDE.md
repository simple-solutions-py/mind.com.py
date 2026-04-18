# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

mind.com.py — static website built with Astro, deployed to GitHub Pages with a custom domain.

## Commands

- `npm run dev` — start dev server (localhost:4321)
- `npm run build` — build static site to `dist/`
- `npm run preview` — preview production build locally

## Architecture

- **Astro** static site generator with strict TypeScript
- Pages live in `src/pages/` — file-based routing
- Static assets in `public/`
- Deployed via GitHub Actions (`.github/workflows/deploy.yml`) to GitHub Pages on push to `master`
