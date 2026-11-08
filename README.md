# CYBER VOCAB

A cyberpunk-styled vocabulary hub. One homepage, four neural-linked terminals. Pick a node, jack in, and study.

**Live site:** https://rifat440.github.io/CYBER-VOCAB/

---

## Terminals

| Card | File | Accent |
|---|---|---|
| GRE Cyber Vocab | `cyberpunk_gre_vocabulary.html` | Cyan `#05d9e8` |
| Cyber Vocab 400 | `cyberpunk_vocab_400_flashcards_1.html` | Yellow `#fcee0a` |
| Cyber Vocab 520 | `cyberpunk_vocab_520_flashcards_1.html` | Pink `#ff2a6d` |
| A-Z Cyber Vocab | `cyberpunk_vocab_az_1925.html` | Purple `#d600ff` |

Each card on the homepage uses the accent color of the page it links to.

## Features

- Cyberpunk hub homepage with neon grid background, scanlines and a glitch title
- Four clickable cards linking to the vocab pages
- Cut-corner cards with neon glow on hover
- Responsive layout (two columns on desktop, one on mobile)
- Keyboard focus styles and `prefers-reduced-motion` support
- Pure HTML and CSS, no build step, no dependencies

## Project structure

```
CYBER-VOCAB/
├── index.html
├── cyberpunk_gre_vocabulary.html
├── cyberpunk_vocab_400_flashcards_1.html
├── cyberpunk_vocab_520_flashcards_1.html
├── cyberpunk_vocab_az_1925.html
└── README.md
```

All links are relative, so `index.html` and the four vocab pages must stay in the same folder.

## Run locally

1. Clone or download the repository.
2. Open `index.html` in any modern browser.

```bash
git clone https://github.com/rifat440/CYBER-VOCAB.git
cd CYBER-VOCAB
```

## Deploy on GitHub Pages

1. Push all files to the repository root.
2. Go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and the `/ (root)` folder, then save.
4. The site goes live at https://rifat440.github.io/CYBER-VOCAB/

## Fonts

Orbitron and Rajdhani are loaded from Google Fonts. Without an internet connection the page falls back to system fonts and everything else still works.

## Customize

- **Card colors:** edit the `.c1` to `.c4` lines in the `<style>` block of `index.html`.
- **Card text and links:** edit the four `<a class="card ...">` blocks in `index.html`.

---

*Stay sharp. Stay neon.*
