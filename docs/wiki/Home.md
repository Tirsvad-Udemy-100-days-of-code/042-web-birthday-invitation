# Birthday Invitation

🌐 **English** · [Dansk](Home-da) · [Bahasa Melayu](Home-ms)

A retro 90s birthday invitation page, built with plain HTML and CSS. Day 42 of
the Udemy "100 Days of Code" web development course.

![The birthday invitation page](images/birthday-invitation.png)

## What the page uses

| Element | Used for |
| --- | --- |
| `<h1>`, `<h2>`, `<h3>` | The title, the date and the section headings |
| `<img>` | The birthday cake, with `alt` text |
| `<ul>` and `<li>` | What the guests bring |
| `<a>` | The Google Maps link to the party |

## Files

| File | Purpose |
| --- | --- |
| `src/index.html` | The page itself |
| `src/style.css` | Colours, font, borders and layout, linked from the page |

## Run it

No build step. Open `src/index.html` in a browser.

## Styling

The styles live in `src/style.css`, not in the HTML. Four custom properties at
the top (`--bg`, `--ink`, `--accent`, `--link`) set the colours, so a new look
is a change of four values.
