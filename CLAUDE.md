# GitHub Profile — Agent Guide

## Docs map

- [Project](docs/project.md): purpose, status and decisions.
- [Documentation index](docs/README.md): feature details and operations.
- [Changelog](CHANGELOG.md): changes and historical coverage.

## Architecture

README.md is the product; .github/ stores repository automation.

## Key Files

`README.md`, `.github/`.

## Patterns & Conventions

Preserve profile presentation; verify public claims with the owner before changing them. Stage explicit paths; never use `git add -A`. Keep secrets and generated output untracked. Record completed changes in CHANGELOG.md.

## Deploy

GitHub renders the profile README. No app server.

## Dev Commands

Review Markdown locally and inspect git diff before committing.

## Gotchas

- Do not copy private project or career notes into the public profile repository.
