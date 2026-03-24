# Learn World Map

An interactive, kid-friendly web app to learn countries, flags, and capitals using a 3D globe game experience.

## Features

- Interactive 3D globe with real country polygons
- Clickable countries with highlighted borders
- Country Explorer panel with:
  - Flag
  - Capital city
  - Fun fact
- Flag Quiz mode (multiple-choice)
- World Tour mode for guided country discovery
- Score, streak, and passport stamp rewards
- Local progress persistence via `localStorage`
- Responsive layout for desktop and mobile

## Tech Stack

- Plain HTML, CSS, JavaScript
- [globe.gl](https://github.com/vasturiano/globe.gl) for 3D globe rendering
- External world GeoJSON for country polygons

## Run Locally

```bash
cd /Users/denishvachhani/Projects/LetsBuild/learn-world-map
python3 -m http.server 8000
```

Open in browser:

- [http://localhost:8000](http://localhost:8000)

## Project Structure

- `index.html` - complete app (UI, styling, game logic, globe interactions)
- `README.md` - project documentation

## How To Play

1. Rotate and zoom the globe.
2. Tap a country to explore details in `Country Explorer`.
3. Tap `Start Quiz` and select the correct flag.
4. Use `Repeat Hint` to hear/see the prompt again.
5. Tap `World Tour` for guided discovery mode.
6. Earn score, streaks, and passport stamps.

## Notes

- Internet connection is required for loading globe assets and country polygon data.
- A hard refresh (`Cmd+Shift+R`) helps after major UI changes.
