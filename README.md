# streakly

Small Vue 3 side project: track daily habits as a heatmap grid

Built for my own use; public in case it helps someone.

## How to use

```bash
# open http://localhost:5173
# click a cell to toggle that day
```

## What it does

- Composition API + script setup
- State persisted to localStorage
- Vite dev setup with hot reload
- GitHub-style contribution grid per habit

## Getting started

```bash
npm install
npm run dev
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── scripts/
│   └── dev.sh
├── src/
│   ├── App.vue
│   ├── config.js
│   └── store.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── package.json
└── vite.config.js
```

## Development

```bash
npm install
npm test
```

## License

MIT licensed, see LICENSE.
