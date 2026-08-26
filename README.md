# 五十音 — Hiragana Practice

A self-quiz web app for learning to read and write hiragana, styled after *genkouyoushi* (Japanese writing practice paper). Single HTML file, no build step, no dependencies.

## Features

- **Write tab** — see the romaji, write the character by hand on paper, tap the practice square to reveal and self-grade ("Got it" / "Keep practicing")
- **Type tab** — see the kana character, type the romaji, get instant right/wrong feedback. Accepts common romanization variants (e.g. `si`/`shi`, `tu`/`tsu`, `nn`/`n`)
- **Chart tab** — a full reference grid of all 71 characters for memorizing; tap any character to watch its stroke order animate, and see which ones you've already mastered
- Real stroke-order animations for every character
- Timed quiz mode (Write and Type tabs) — score, accuracy, and time at the end
- Practice sequentially by line (あ行, か行, …) or fully randomized
- "Missed only" filter to drill just the characters you're struggling with
- Jump straight to a single line instead of cycling through all 71
- Daily streak tracker
- Progress, settings, and position are saved automatically in the browser — reopen the app and pick up exactly where you left off
- Share or copy a summary of your mastery progress

## Covers

All 46 base hiragana (gojūon) plus the 25 dakuten/handakuten characters (が, ざ, だ, ば, ぱ rows) — 71 characters total.

## Usage

Open `hiragana-practice.html` in any browser — no install needed.

To host it live with GitHub Pages: **Settings → Pages → Deploy from a branch → main → / (root)**. It'll be served at:

```
https://<your-username>.github.io/<repo-name>/hiragana-practice.html
```

## Tech

Plain HTML, CSS, and vanilla JavaScript. Fonts loaded from Google Fonts (Shippori Mincho, Noto Sans JP, Zen Kaku Gothic New). Progress is stored via the browser's local storage — nothing leaves your device.

## Credits

Stroke-order path data is sourced from the [KanjiVG](https://kanjivg.tagaini.net) project by Ulrich Apel, licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).

## License

MIT for the app code. Stroke-order data retains its original CC BY-SA 3.0 license — please keep the KanjiVG attribution above if you redistribute or fork this project.
