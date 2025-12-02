# barejs

Bare-bones Node.js starter that gives you the minimum needed to run and test Typescript locally.

## Prerequisites
- Node.js 18+ (for `node --watch` support).
- npm (ships with Node).
- VSCode (debug-ready via `.vscode/launch.json` – use the "Launch Program" config).

## Quick start
1) Install deps
```bash
npm install
```
2) Run main (restarts on file changes)
```bash
npm start
```
3) Run tests
```bash
npm test
```

## Project layout
```
.
├── src/
│   ├── index.js        # entry point; logs "Hello world"
│   └── index.test.js   # placeholder Jest suite
├── jest.config.js      # Node test env, 5s timeout
└── package.json        # scripts and metadata
```

## License
MIT. See `LICENSE`.
