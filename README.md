# ai-a11y

[![npm version](https://img.shields.io/npm/v/ai-a11y.svg)](https://www.npmjs.com/package/ai-a11y)
[![npm downloads](https://img.shields.io/npm/dm/ai-a11y.svg)](https://www.npmjs.com/package/ai-a11y)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-a11y)](https://github.com/lxgic-studios/ai-a11y/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)

Scan your HTML and JSX files for accessibility issues. Get WCAG-based suggestions with actual code fixes.

## Why Accessibility Matters

- **Legal compliance**: WCAG 2.1 AA is required by ADA, Section 508, and EU accessibility laws
- **SEO boost**: Accessible sites tend to rank better (semantic HTML, proper headings, alt text)
- **Larger audience**: 15% of people have some form of disability
- **Better UX**: Accessibility improvements benefit all users (keyboard nav, clear contrast)

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

npx ai-a11y ./src --fix
# Auto-fix issues where possible

npx ai-a11y ./src --output report.json
# Export detailed report
```

## What It Checks

- Missing or empty alt text on images
- Low color contrast ratios
- Missing form labels and ARIA attributes
- Improper heading hierarchy (h1 → h3 skipping h2)
- Missing landmark roles
- Keyboard accessibility issues
- Focus management problems

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT

---

**Built by [LXGIC Studios](https://lxgicstudios.com)**

GitHub: https://github.com/lxgicstudios
Twitter: https://x.com/lxgicstudios

Want more free tools like this? We have 40+ on our GitHub: github.com/lxgicstudios
