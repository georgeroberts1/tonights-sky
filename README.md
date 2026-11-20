# Tonight's Sky

A single-page night-sky guide. Pick a town and it shows the sky above it right now: the Moon, the planets and the brighter stars, with a plan for what's worth looking at tonight.

**Live site:** https://georgeroberts1.github.io/tonights-sky/

## What it does

- **Interactive sky.** Drag to look around, zoom in and out, and tap an object to see what it is.
- **Time slider.** Scrub through the night, or press *Play the night* to watch the sky turn.
- **Tonight's plan.** Lists where the Moon and each planet are, picks out stars worth finding, and points out close pairings and meteor showers when they're happening.
- **The family's skies.** Small sky maps for other towns at the same moment, so you can compare. You can add more towns.
- **Red-light mode.** Turns the whole page red so it doesn't spoil your night vision when you use it outside.

## How it works

The page doesn't use any sky service or API. Your browser works out every position itself, from the orbits of the planets and the Moon, using a built-in star catalogue and list of towns. Everything (code, data and styles) is in one file, `index.html`. The only thing it loads from outside is web fonts from Google Fonts.

The page says its planet positions were checked against an independent reference and came out within about a tenth of a degree.

## Running it locally

There's nothing to build. Open `index.html` in a browser, or serve the folder:

```sh
python -m http.server
```

then go to http://localhost:8000.

## Credits

Designed and written by Claude, Anthropic's AI model, in a conversation with the repo owner.
