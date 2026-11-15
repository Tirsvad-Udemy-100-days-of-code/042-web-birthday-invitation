# Manual test checklist: Birthday Invitation page

Open `src/index.html` in a browser (see the README). Mark each item `Pass` or
`Fail` and note the date and browser.

Last run: 2026-11-16, built-in browser pane (Chromium), page served from a throwaway local static server on 127.0.0.1 so that `style.css` loads. Items 1 to 5 and 8 were read from the DOM; item 6 from the computed style and the resource list; item 7 at a 375 px wide viewport (scroll width equals client width).

| # | Check | Expected | Result |
| --- | --- | --- | --- |
| 1 | Exactly one `h1` | Text is "It's My Birthday!" | Pass |
| 2 | Exactly one `h2` | Text is "On the 12th May" | Pass |
| 3 | Exactly one `img` | It has the `alt` text "purple birthday cake with candles" and the picture loads | Pass |
| 4 | The first `h3` is directly followed by a list | "What to bring:" is followed by a `ul` with three `li` | Pass |
| 5 | The second `h3` is directly followed by a link | "This is where you need to go:" is followed by an `a` whose `href` starts with `https://www.google.com/maps/` | Pass |
| 6 | The stylesheet is applied | `style.css` is requested and the page background is yellow (`rgb(255, 235, 59)`) | Pass |
| 7 | Narrow window (375 px wide) | Text wraps and nothing scrolls sideways | Pass |
| 8 | Page title | The tab shows "It's My Birthday!" | Pass |
