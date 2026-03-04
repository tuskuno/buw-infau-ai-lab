# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repo Is

A hands-on workshop ("From Prompt to Web App") for Bauhaus InfAU staff. Participants use Claude Code to build web apps during a 2-hour session. This repo contains the workshop guide, starter data, and a `results/` folder where participant projects are published to GitHub Pages.

**Target audience:** Non-developers without prior web experience. All prompts and instructions should be beginner-friendly.

## Repository Structure

- `workshop/README.md` — Main workshop guide (Parts 0–5), the primary file you'll edit
- `workshop/prompts/` — Printable prompt cards for each project (A–D)
- `workshop/data/weimar/` — GeoJSON files (buildings, streets, plots) exported from Rhino via Heron plugin
- `workshop/cheatsheet.md` — Claude Code quick reference for participants
- `results/` — Participant projects, each in a subfolder (e.g., `results/alice/`). Deployed to GitHub Pages
- `results/index.html` — Auto-listing landing page (uses GitHub API, no maintenance needed)
- `.github/workflows/deploy-pages.yml` — Deploys `results/` to Pages on push to main

## Deployment

GitHub Pages serves `results/` at `https://bauhaus-infau.github.io/ai-lab/`. The workflow triggers only on changes to `results/**`. Repo settings must have Pages source set to "GitHub Actions".

## Data Notes

The Weimar GeoJSON files have coordinates near (0, 0) — not real-world lat/lon — because Heron exports from Rhino's local coordinate system. Projects using this data should use SVG/Canvas rendering, not map libraries like Leaflet that expect geographic coordinates.

## Participant Publishing Flow

Participants clone this repo, copy their built files into `results/<name>/`, create a branch (`add-<name>`), and open a PR. The instructor merges it. This avoids merge conflicts from simultaneous pushes.
