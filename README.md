# pyastral-toolkit

A Dockerized Python development environment featuring [Astral](https://astral.sh/)'s modern toolchain for fast, reliable Python development.

>However, bear in mind that although guys at Astral are doing an incredible job adding all those features and bugfixes to their ecosystem of rust-based
tools, some of the features might still be missing and some bugs will certainly be there. Just remember that those Astral tools might not yet be matured
>enough to be used in production environemnt so tread cautiosuly there - You've been warned!

## What's Inside

This image comes pre-configured with Astral's ecosystem of Python tools:

- **[uv](https://github.com/astral-sh/uv)** - Blazing-fast Python package installer and resolver (100x faster than pip)
- **[ruff](https://github.com/astral-sh/ruff)** - An extremely fast Python linter and code formatter
- **[ux](https://github.com/astral-sh/ux)** - Python development tools and utilities
- **[ty](https://github.com/astral-sh/ty)** - Python type checker and language server

Plus VS Code integration with pre-configured extensions and settings.

On top of that, it's also inteded to work with VS Code via .devcontainers so that it

## Why Use This Image?
- **VS Code Dev Containers ready** - Clone and start coding in a fully configured environment
- **Consistent environment** - Same tooling across your entire team
- **Zero installation** - No need to install Python, uv, ruff or ty locally
- **CI/CD ready** - Perfect for GitHub Actions, GitLab CI, etc.

## Quick Start

## Quick Start

### With VS Code Dev Containers

1. **Clone this repository** (or use it as a template for your own project)
2. Install the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
3. Open the repository in VS Code
4. When prompted, click "Reopen in Container" (or run Ctrl+Shift+P → "Dev Containers: Reopen in Container")

That's it! The `.devcontainer/devcontainer.json` in this repo will automatically configure everything with settings for the Astral toolchain.
