# BCOS Badge Generator

A web tool for generating BCOS certification badges.

**Live Demo**: https://daletyler1737.github.io/bcos-badge-generator/

## Features

- Enter cert ID or GitHub repo URL
- Live badge preview
- Multiple badge styles (flat, flat-square, for-the-badge, social)
- Copy Markdown or HTML embed code
- Matches rustchain.org vintage terminal aesthetic

## Usage

1. Visit the [live demo](https://daletyler1737.github.io/bcos-badge-generator/)
2. Enter your BCOS cert ID (e.g., `bcos_abc123`) or GitHub repo URL
3. Select badge style
4. Preview badge
5. Copy embed code

## Badge API

- Badge endpoint: `https://50.28.86.131/bcos/badge/{cert_id}.svg`
- Verify page: `https://rustchain.org/bcos/verify/{cert_id}`

## Example

```markdown
[![BCOS](https://50.28.86.131/bcos/badge/BCOS-TEST.svg?style=flat)](https://rustchain.org/bcos/verify/BCOS-TEST)
```
