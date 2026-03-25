# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a static personal website for Pasi Seppänen, hosted on GitHub Pages at `seppanen.eu`. There is no build step, framework, or package manager — the site is plain HTML/CSS served directly.

## Deployment

Changes pushed to the `main` branch are automatically deployed via GitHub Pages. The `CNAME` file maps the custom domain `seppanen.eu`.

To deploy: `git push` to `main`.

## Structure

- `index.html` — the entire site (single-file, self-contained HTML/CSS)
- `CNAME` — GitHub Pages custom domain config (do not modify)
