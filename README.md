# Obsidian Chess PGN/FEN Viewer

This plugin allows you to view chess games (PGN) and positions (FEN) directly in your Obsidian notes using the `@mliebelt/pgn-viewer` library.

## Features

- **PGN Viewer**: Render full chess games with move lists and navigation.
- **FEN Viewer**: Display static chess positions (boards).
- **Customizable Size**: Adjust the board size via a slider in the plugin settings.
- **Responsive Layout**: Designed to look great within Obsidian's interface.

## Usage

### 1. Rendering PGN
To display a chess game, use the `pgn` code block:

```pgn
1. e4 e5 2. Nf3 Nc6 3. Bb5 a6 4. Ba4 Nf6 5. O-O Be7
```

### 2. Rendering FEN
To display a specific board position, use the `fen` code block:

```fen
rnbqkbnr/pp1ppppp/8/2p5/4P3/8/PPPP1PPP/RNBQKBNR w KQkq c6 0 2
```

## Settings

Go to `Settings` -> `Chess PGN/FEN Viewer` to adjust the **Board Size**. The size is updated in real-time.

## Installation

### From GitHub (Manual)
1. Download the latest release (`main.js`, `manifest.json`, `styles.css`).
2. Create a folder named `obsidian-chess-plugin` in your vault's `.obsidian/plugins/` directory.
3. Move the downloaded files into that folder.
4. Reload Obsidian and enable the plugin in `Settings` -> `Community plugins`.

---

## Development

If you want to build the plugin yourself:

1. Clone the repository.
2. Install dependencies: `npm install`.
3. Build the plugin: `npm run build`.

## Credits

This plugin is powered by the excellent [pgn-viewer](https://github.com/mliebelt/pgn-viewer) library by Markus Liebelt.

## License
MIT
# obsidian-chess-viewer
# obsidian-chess-viewer
