# focusfolio-kit

MV3 extension playground: page reading-time estimator

Started as a weekend hack, grew on me.

## Features

- Popup shows today's total focus time
- Per-tab time persisted to chrome.storage
- No remote calls, everything stays local
- Manifest V3, service worker based

## Examples

```bash
# click the toolbar icon to see today's reading time
```

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## Why

Needed this for myself; figured others might too.
