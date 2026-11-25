# BASE ARCHITECT

A 3D, 44 × 44 grid designer for planning Clash of Clans village layouts. Paint, erase and recolour 1,936 tiles on a WebGL board you can orbit, pan and zoom. Built with React, Three.js and React Three Fiber.

## Download the complete source

The complete project is included in **[base-architect-source-v1.0.0.zip](base-architect-source-v1.0.0.zip)**. It contains the application source, UI, 3D scene, tests, configuration, README and MIT license.

1. Download the ZIP from this repository.
2. Extract it.
3. Open the extracted `base-architect` folder in a terminal.
4. Use Node.js 18 or newer, then run:

```bash
npm install
npm run dev
```

To create a production build or run the logic tests:

```bash
npm run build
npm test
```

## What's included

- 44 × 44 editable grid (1,936 cells)
- 3D board with orbit, pan and zoom controls
- Paint, erase, recolour, undo and redo
- Multiple layouts with local persistence
- JSON import/export and PNG export
- Automated tests for grid logic, history, import/export and storage

## Technology

React 18 · Three.js · React Three Fiber · Vite

## Project status

The source archive is published here for download. The automated logic test suite was run before publishing: **21 tests passed**. The 3D interface still needs to be checked in a browser on the target device.

## License and attribution

Copyright (c) 2026 kxvior. Released under the MIT License. See [LICENSE](LICENSE).
