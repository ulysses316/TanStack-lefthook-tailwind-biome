# TanStack Start + Bun + Biome + Lefthook Template

This project is a minimal **Hello World** template based on [TanStack Start](https://start.tanstack.com/), configured with:

- **Bun** as the package manager
- **Biome** as the linter and code formatter
- **Lefthook** for fast and reliable pre-commit hooks

## Features

- ⚡ Super fast setup with **Bun**
- 🧹 Consistent code style and linting via **Biome**
- 🛡️ Git hooks powered by **Lefthook** to enforce code quality
- 🚀 Ready to customize and build your own TanStack app

## Getting Started

### 1. Install Dependencies

```bash
bun install
```
### 2. Run the Development Server

```bash
bun run dev or node --run dev
```
The app will be available at http://localhost:3000.

### 3. Format and Lint

You can manually run Biome:

```bash
bun run lint or bunx biome check --fix
```

### 4. Prepare Git Hooks

Install Lefthook hooks:

```bash
bunx lefthook install
```

Lefthook will automatically run linting and formatting before each commit.
