# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v1.3.0] - 2026-09-02

### Added
- Vulnerability scanning with govulncheck (part of `task fmt` and a CI step)
- gofumpt pinned via the go.mod `tool` directive (no global install needed)

### Changed
- Upgraded Go to 1.27
- Upgraded golangci-lint to v2.13.2 and its GitHub Action to v9
- Upgraded GitHub Actions: checkout to v7, setup-go to v7
- CI test step now runs `task test` to keep test flags in one place

### Removed
- Stale `.gitignore` entries left over from other projects (terraform, serverless, credentials)

## [v1.2.0] - 2025-10-14

### Changed
- Upgraded go to 1.25

## [v1.1.0] - 2025-07-13

### Added
- GitHub issue templates for bug reports and feature requests
- GitHub pull request template with comprehensive checklist

## [v1.0.0] - 2025-07-01

### Added
- Initial project template structure
- Basic Go module setup with Go 1.24
- Comprehensive linting configuration with golangci-lint
- Task automation with Taskfile.yml
- Alternative Make targets for development
- GitHub Actions CI workflow
- Claude Code guidance documentation (CLAUDE.md)
- Changelog documentation following Keep a Changelog format

### Changed

### Deprecated

### Removed

### Fixed

### Security