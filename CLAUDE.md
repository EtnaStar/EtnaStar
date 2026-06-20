# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the **EtnaStar** GitHub profile README repository (`EtnaStar/EtnaStar`). A repository with the same name as a GitHub username automatically displays its `README.md` on the GitHub profile page.

## Setup

Clone and configure:
```
gh repo clone EtnaStar/EtnaStar .
```

Or using git:
```
git clone https://github.com/EtnaStar/EtnaStar.git .
```

## Structure

- `README.md` — The GitHub profile page content. This is the only required file; it renders automatically on the GitHub profile.
- Any images or assets referenced in `README.md` should be committed alongside it.

## Workflow

The only "build" step is pushing to `main` — GitHub renders `README.md` as Markdown on the profile automatically.

To preview locally, use any Markdown previewer (VS Code built-in: `Ctrl+Shift+V`).

To publish changes:
```
git add README.md
git commit -m "update profile"
git push
```

## Content Guidelines

- The profile README should reflect the user's identity as a developer/creator.
- Keep the `README.md` concise and visually engaging — GitHub renders standard Markdown and HTML.
- Dynamic content (GitHub stats, badges, etc.) is embedded via external URLs pointing to services like `github-readme-stats.vercel.app`.
