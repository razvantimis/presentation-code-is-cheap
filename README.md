# Code is cheap. Design is not.

How I work with coding agents. A 7-minute JSHeroes meetup talk.

**View it:** https://razvantimis.github.io/presentation-code-is-cheap/

## Keys

- `→` / `Space` / click right half: next slide. `←` / click left half: previous.
- `N`: speaker notes. `F`: fullscreen.
- `#5` in the URL opens slide 5.

## Layout

- `deck.json` sets the slide order.
- `slides/<id>.html` holds one `<section>` per slide, with speaker notes in `<aside>`.
- `deck.css` holds the shared styles. Each slide is drawn on a 1920×1080 canvas.
- `index.html` loads the slides and scales the canvas to the window. There is no build step.

Run it locally with any static server, e.g. `python3 -m http.server`, because the slides load through `fetch`.
