# AGENTS.md

Instruktioner för automationsagenter (Claude Code, Codex) i det här repot.

## Repot

- **Namn:** `orangeelefant/stadly-social-assets`
- **Syfte:** Bildhotell för Städlys inlägg i sociala medier. Bilderna serveras via jsDelivr från `main`.
- **Drift:** Ingen deploy.

## Husregler

- Byt aldrig namn på, flytta eller ta bort en bild. Publicerade och schemalagda inlägg pekar på URL:en.
- Pusha direkt till `main`. En logisk ändring per commit.
- Inga `.env`-filer, nycklar eller inloggningsuppgifter i repot.

## Efter varje ändring

En punkt under `## [Unreleased]` i `CHANGELOG.md` och avstämd `TODO.md`, i samma commit.
