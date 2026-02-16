# Demo Prompter

A browser-based teleprompter for remote demos and presentations. Paste or upload a markdown script, hit Start, and let it scroll while you present.

## Features

- **Markdown rendering** — `#` headings, `- ` bullets, `**bold**`, `*italic*`, inline `code`, blockquotes, horizontal rules
- **Upload .md files** or drag-and-drop
- **Adjustable speed & text size** — before and during playback
- **Keyboard controls** — Space (pause/play), ↑↓ (speed), ←→ (jump), Home (top), Esc (edit)
- **Click to pause/resume** — click anywhere in the text area
- **Focus highlight** — active line brightens at 35% from top
- **Independent timer** — starts on play, survives scroll pauses, manual pause/reset buttons
- **Scrollbar** — drag to jump to any position
- **Mirror mode** — for physical teleprompter setups
- **Window-focus aware** — clicking to bring window to front won't toggle pause

## Usage

1. Open `index.html` in any modern browser
2. Paste your script or click **Upload .md** to load a markdown file
3. Adjust **Speed** and **Size** sliders
4. Click **Start** — markdown renders and auto-scroll begins

### Keyboard Shortcuts (during playback)

| Key | Action |
|-----|--------|
| `Space` | Pause / resume scrolling |
| `↑` `↓` | Adjust scroll speed |
| `←` `→` | Jump backward / forward |
| `Home` | Back to top + reset timer |
| `Esc` | Return to edit mode |

## Hosting

Single self-contained HTML file — no build step, no dependencies. Options:

- **Local:** Just open `index.html`
- **GitHub Pages:** Enable Pages in repo settings → serves at `https://yourusername.github.io/demo-prompter/`
- **Any static host:** Drop the file anywhere

## License

MIT
