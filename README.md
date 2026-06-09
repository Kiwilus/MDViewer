# MDViewer
A clean, minimal desktop app for reading Markdown files — with drag & drop support, dark mode, and beautiful typography.

Built with HTML/CSS/JS and packaged as a native desktop app using [Electron](https://www.electronjs.org/).

---

## Features

- Drag & drop `.md`, `.markdown`, or `.txt` files onto the window
- Renders tables, code blocks, blockquotes, lists, and more
- Automatic dark mode (follows your OS setting)
- Syntax-highlighted inline code
- Demo mode to try it out instantly

## Download

Head to the [Releases](../../releases) page to download the latest version for your platform.

| Platform | File |
|----------|------|
| Windows  | `Markdown.Viewer.Setup.1.0.0.exe` |
| Linux    | `Markdown.Viewer-1.0.0.AppImage` |

## Development

**Requirements:** [Node.js](https://nodejs.org) (LTS)

```bash
# Clone the repo
git clone https://github.com/Kiwilus/MDViewer.git
cd MDViewer

# Install dependencies
npm install

# Run in development
npm start
```

## Build from source

```bash
# Windows
npm run build:win

# macOS
npm run build:mac

# Linux
npm run build:linux
```

Output will be in the `dist/` folder.

## Tech stack

- [Electron](https://www.electronjs.org/) — desktop app framework
- [marked.js](https://marked.js.org/) — Markdown parser
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) + [Lora](https://fonts.google.com/specimen/Lora) + [JetBrains Mono](https://www.jetbrains.com/lp/mono/) — fonts

## License

MIT