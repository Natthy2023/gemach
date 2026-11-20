# Gemach — Number Guessing Game

Gemach is a lightweight, browser-based number guessing game built with **HTML5, CSS, JavaScript, and the HTML5 Canvas API**. A secret number between 1 and 100 is selected at the start of each round. The player has 10 attempts to guess it, with a hint after every valid guess.

## Features

- Random secret number between **1 and 100**
- Helpful **Too Low** and **Too High** hints
- Maximum of **10 attempts** per round
- Attempts-used and attempts-left counters
- Progress bar showing guesses used
- Previous-guesses history
- Win and game-over messages
- New Game button to restart with a fresh number
- Enter key support for submitting guesses
- Animated particle background rendered with HTML5 Canvas
- Responsive layout for mobile and desktop
- No frameworks, external libraries, backend, or build tools required

## How to Play

1. Open the game in a modern web browser.
2. Enter a whole number from 1 to 100.
3. Select **Submit Guess** or press **Enter**.
4. Follow the hint:
   - **Too LOW:** choose a higher number.
   - **Too HIGH:** choose a lower number.
   - **Correct:** you found the secret number and won!
5. If you use all 10 attempts without guessing correctly, the game reveals the secret number.
6. Select **New Game** to play another round.

## Run Locally

Gemach uses a single file, so no installation is needed.

1. Download or clone this project.
2. Locate `index.html`.
3. Open `index.html` in Chrome, Firefox, Edge, Safari, or another modern browser.

### Optional: Run with a local development server

If you prefer to serve the file locally, you can use Python:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

## Project Structure

```text
gemach/
└── index.html
```

All HTML markup, CSS styling, and JavaScript game logic are contained in `index.html`.

## Technologies

- **HTML5** — page structure and Canvas element
- **CSS3** — responsive layout, styling, and animations/transitions
- **JavaScript** — random number generation, game rules, hints, and UI updates
- **HTML5 Canvas API** — animated particle background

## Customization

You can edit `index.html` to customize the game:

- Change the number range in the game logic and the displayed instructions.
- Change `MAX_ATTEMPTS` to adjust the number of guesses allowed.
- Update the colors, spacing, and typography in the `<style>` section.
- Adjust the particle count and movement in the Canvas section.

When changing the number range, update the input validation and on-screen instructions as well.

## License

Choose and add a license before distributing or reusing this project publicly. No license is specified by default.
