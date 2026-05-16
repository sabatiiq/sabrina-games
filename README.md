# Bear's Game Land 🐻🍪

A little collection of browser games for early learners (age 6 and up). All games share a friendly Bear character and a cookie theme.

**Live site:** https://sabatiiq.github.io/sabrina-games/

## Games

| Game | What it teaches | File |
|------|-----------------|------|
| 🍪 Cookie Catcher | Reflexes, decision making | [cookie-game.html](cookie-game.html) |
| 📖 Storybook Adventure | Early reading, sight words | [reading-game.html](reading-game.html) |
| ➕ Cookie Math | Addition, subtraction within 20, missing addend | [math-game.html](math-game.html) |
| 🍄 Super Plumber | Platformer — jumping, timing | [mario-game.html](mario-game.html) |
| 👩‍🍳 Cookie Bakery | Sequencing, following multi-step instructions | [baking-game.html](baking-game.html) |
| 👨‍👩‍👧‍👦 Bear's Family | Family vocabulary, matching, listening | [family-game.html](family-game.html) |

## Tech

Plain HTML / CSS / JavaScript. No build step, no dependencies. Each game is one self-contained file you can open directly in a browser. Uses the browser's built-in Speech Synthesis API for read-aloud support.

## Running locally

Just open `index.html` in a browser, or run any local static server:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000
