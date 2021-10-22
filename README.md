# vscode-eslint-1355

## Bug reproduction steps

- Open index.ts
- Ctrl+Shift+P (command palette) > Format document

## How I setup the project...

- `npm init -y`
- `npx tsc init`
- `npx eslint --init`
  - TypeScript: yes
  - Style guide: Standard
- Copy settings.json from my broken project
