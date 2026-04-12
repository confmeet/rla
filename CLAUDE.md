# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is the static website for the Inaugural Midwest Randomized Linear Algebra (RLA) Workshop (Madison, WI, May 11–12, 2026). The entire site is a single `index.html` file using the [Bulma](https://bulma.io/) CSS framework (v1.0.4) loaded via CDN.

There are no build tools, package managers, or frameworks — changes to `index.html` are the changes to the site.

## Development

To preview the site locally, open `index.html` directly in a browser or serve it with any static file server, e.g.:

```bash
python3 -m http.server
```

## Structure of `index.html`

The page is divided into `<section>` elements with IDs:

- `#title` — Workshop title, date, and hero image
- `#logistics` — About, Venue & Hotel, and Interest Form subsections
- `#agenda` — Two-day schedule tables (`#may11`, `#may12`)
- `#questions` — Contact information (Vivak Patel and D. Adrian Maldonado)

Content is laid out using Bulma's column grid (`columns` / `column is-half`).
