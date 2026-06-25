# 🌙 An Evening of Time

A deeply personal interactive narrative game built with vanilla HTML, CSS, and JavaScript.

Walk through a moonlit world and collect items given to you by the people who shaped you — The Little Boy, The Op-Shop Woman, The Tall Woman, The Nine-Finger Wise Woman, DJ Daddy Cool, and more. Each item carries meaning, a hidden message, and unlocks something new.

---

## ✨ Features

- **21 collectible items** — each with meaning, a hidden message, and an unlock
- **8 narrative chapters** — from Moonlit Arrival to the Final Chapter
- **Character-driven inventory** — items are gifted by named characters
- **Hidden messages** — revealed when you collect each item
- **Chapter-gated events** — some scenes require specific items
- **Fully offline** — no dependencies, no build step, single HTML file option

---

## 🎮 How to Play

1. Open `index.html` in any modern browser
2. Collect items from the panel on the left
3. Watch the story unfold in the narrative panel
4. Advance chapters once you feel ready
5. Discover hidden messages and unlock special scenes

---

## 📁 Project Structure

```
an-evening-of-time/
├── index.html              # Main entry point (self-contained game)
├── assets/
│   ├── css/
│   │   └── style.css       # All styles
│   └── js/
│       └── game.js         # All game logic
├── docs/
│   ├── items.md            # Full item reference with meanings & hidden messages
│   └── characters.md       # Character profiles
├── README.md
└── LICENSE
```

---

## 🧩 Items & Characters

| Item | From | Unlocks |
|------|------|---------|
| Feather | The Little Boy | River Memory scene |
| Stone | The Little Boy | Time Loop moment |
| Calculator | The Little Boy | Calculator wall puzzle |
| McDonald's Bag | The Little Boy | Memory cutscene |
| Pasta | The Little Boy | Kitchen memory |
| Ring | The Op-Shop Woman | Tall Woman's corridor |
| Puffer Jacket | The Op-Shop Woman | Deep Forest chapter |
| Coffee Cup | The Op-Shop Woman | Hidden scene with DJ Daddy Cool |
| Metamucil | The Op-Shop Woman | Comedic fairy message |
| Titanium Ring | The Op-Shop Woman | Wise Woman's blessing |
| Soju | The Op-Shop Woman | Late-night dialogue |
| Sofa | The Op-Shop Woman | Cozy hidden scene |
| Notebook | The Tall Woman | Hidden willow dialogue |
| Vitamins | The Tall Woman | Time Loop energy boost |
| TV | The Tall Woman | Time Loop vision |
| Key | The Nine-Finger Wise Woman | Final chapter |
| DJ Spin Table | DJ Daddy Cool | His personal chapter |
| Computer | DJ Daddy Cool | Final hidden message |
| Willow Leaf | The Willow Tree | Ending requirement |
| Moon Halo | The Moon | Hidden sky text |
| Fairy Sparkle | The Fairy | Sparkle-trail puzzle |

---

## 🚀 Running Locally

No build step required. Just open the file:

```bash
git clone https://github.com/YOUR-USERNAME/an-evening-of-time.git
cd an-evening-of-time
open index.html   # macOS
# or
start index.html  # Windows
# or
xdg-open index.html  # Linux
```

Or serve it locally:

```bash
npx serve .
# then visit http://localhost:3000
```

---

## 🌱 Development Notes

This game is intentionally built without frameworks. The entire experience lives in plain HTML, CSS, and JavaScript — easy to read, easy to modify, easy to carry.

To add a new item:
1. Add it to the `ITEMS` array in `assets/js/game.js`
2. Add any unlock logic to the `handleUnlock()` function
3. Document it in `docs/items.md`

---

## 📄 License

MIT — do what you need with it.
