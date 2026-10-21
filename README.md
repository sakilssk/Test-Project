# Test-Project

A Node.js workspace for experimenting and iterating on small features.

## Requirements

- [Node.js](https://nodejs.org/) (LTS recommended)
- npm (bundled with Node.js)

## Setup

```bash
npm install
```

Environment variables are loaded with [`dotenv`](https://www.npmjs.com/package/dotenv). Copy any secrets you need into a local `.env` file (do not commit it).

## Project layout

| Path | Purpose |
|------|---------|
| `package.json` | Project metadata and dependencies |
| `cursor.md` | Workspace notes for Cursor |

The package entry point is `index.js` (`"main"` in `package.json`). Add application code there as the project grows.

## Scripts

| Script | Description |
|--------|-------------|
| `npm test` | Placeholder — no tests are defined yet |

## License

ISC
