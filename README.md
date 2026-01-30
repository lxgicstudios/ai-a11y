# ai-a11y

[![npm version](https://img.shields.io/npm/v/ai-a11y.svg)](https://www.npmjs.com/package/ai-a11y)
[![npm downloads](https://img.shields.io/npm/dm/ai-a11y.svg)](https://www.npmjs.com/package/ai-a11y)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-a11y)](https://github.com/lxgic-studios/ai-a11y/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Scan your HTML and JSX files for accessibility issues. Get WCAG-based suggestions with actual code fixes.

## Install

```bash
npm install -g ai-a11y
```

## Usage

```bash
npx ai-a11y ./src/components/Header.tsx
# Scans a single file

npx ai-a11y ./src/components/
# Scans all HTML/JSX files in a directory
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
