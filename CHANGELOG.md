# Changelog

All notable changes to this standalone edition of free-for-dev are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit, plus an entry for it in the README Table of Contents.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions updates (the repo has no package manifests, so no language ecosystem applies).
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow — the repository's first workflow, since upstream ships none); the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).
- Licence flag recorded: no licence file and no licence statement exists anywhere in the upstream tree. Nothing was added or changed in this respect.

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev) at upstream commit `7b6b99725015d0e648d987679ddf1d650b157a7c` (upstream HEAD dated 2026-10-20).
- Fork history severed; all files preserved exactly as-is, including `logo.webp` (no licence file exists upstream — see the licence flag under v1.1.0).
