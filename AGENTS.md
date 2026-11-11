# AGENTS.md

Instructions for automation agents (Claude Code, Codex) in this repo.

## The repo

- **Name:** `orangeelefant/stadly-social-assets`
- **Purpose:** An image store for the social media posts of Städly. jsDelivr serves the images from `main`.
- **Operation:** No deploy.

## House rules

- Never rename, move or delete an image. Published and scheduled posts point to the URL.
- Push directly to `main`. Make one logical change in each commit.
- Never put `.env` files, keys or credentials in the repo.

## After every change

Add one bullet under `## [Unreleased]` in `CHANGELOG.md`. Correct `TODO.md`. Do both in the same commit.
