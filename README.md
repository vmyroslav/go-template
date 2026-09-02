[![Action Status](https://github.com/vmyroslav/go-template/actions/workflows/ci.yaml/badge.svg)](https://github.com/vmyroslav/go-template/actions/workflows/ci.yaml)

# Go Template

A minimal Go project template with comprehensive linting, testing, and CI/CD setup.

## Features

- Go 1.27 with tooling
- Linting with golangci-lint
- Vulnerability scanning with govulncheck
- Task automation with Taskfile
- GitHub Actions CI/CD
- Release management with changelog automation

## Quick Start

### Prerequisites

- Go 1.27 or later
- [Task](https://taskfile.dev/) for task automation

### Development Commands

- `task` - Show all available tasks
- `task test` - Run tests with coverage
- `task lint` - Run linter checks
- `task fmt` - Tidy dependencies, format code, and scan for vulnerabilities

### Release Process

```bash
task ci:prepare-release VERSION=1.0.0
```

This validates the version bump, extracts release notes from CHANGELOG.md, and updates the changelog.