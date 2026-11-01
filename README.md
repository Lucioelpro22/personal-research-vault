# Research Vault

A polished personal research workspace for collecting links, PDFs, and notes, then turning them into connected, source-backed insights.

**[Open the live app](https://personal-research-vault.lucianohernanleal22.chatgpt.site)**

## Features

- Unified library for links, PDFs, and personal notes
- Full-text search and source-type filters
- Card and compact list views
- Source summaries with inline citations
- Related-reading and connection discovery
- Interactive knowledge map
- Browser-local persistence
- Favorites and live library statistics
- JSON backup and restore
- Responsive interface for desktop and mobile
- Lightweight, dependency-free static build

## Project structure

```text
dist/
  index.html    Application shell
  styles.css    Responsive visual system
  enhancements.css  v2 interaction and graph styles
  app.js        Demo data and interactions
.openai/
  hosting.json  OpenAI Sites deployment configuration
```

## Run locally

Serve the repository root with any static HTTP server, then open `dist/index.html`. For example:

```bash
npx serve dist
```

## Status

Version 2 is a functional local-first prototype: additions, favorites and deletions persist in the browser, while JSON export/import provides portable backups. Automated PDF extraction and model-backed synthesis are the next production integration layer.

## License

MIT © 2026 Luciano Leal

