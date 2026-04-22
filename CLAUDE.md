# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a minimal static HTML project — a single self-contained greeting card page for New Year 2026. There is no build system, package manager, framework, or test suite.

## Structure

```
index.html   — The entire application: HTML, CSS, and JS in one file
test1.txt    — Plain text file
test2.txt    — Plain text file
test3.txt    — Plain text file
```

## Running the Project

Open `index.html` directly in a browser. No build step, server, or dependency installation is required.

## Architecture

`index.html` is fully self-contained:

- **CSS** (embedded in `<style>`): Dark radial-gradient background, glassmorphism card, gold gradient text with a glow animation, and falling confetti particle styles.
- **JavaScript** (embedded in `<script>`): Generates 50 confetti `<div>` elements at random horizontal positions and animation delays, appended to `<body>` at page load.

There are no external dependencies, no imports, and no module system.
