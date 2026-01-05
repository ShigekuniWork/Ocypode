# Development Guidelines

This guidelines for developing code changes.

## Repository Management

This repository uses `moon` for managing multi-language monorepo.

> [!IMPORTANT]
> **Always use moon-based commands instead of language-specific build tools directly.** For example, use `moon run` instead of `cargo build`, `npm run`, or other language-specific commands. This ensures consistent workflows across all projects in the monorepo.
