# If You Ain't 1st, You're Last

Static league page for a Sleeper fantasy football keeper league — the current
keeper board and what each one costs, the keeper rankings, the draft board,
everyone's two-year clock, and the league rules.

Published with GitHub Pages. It is a single self-contained `index.html`: no
build step, no server, no API calls. The only external requests are Google
Fonts, and the only browser API used is `localStorage`, which remembers which
team you picked so the page can highlight your rows. That selection never
leaves your own browser.

The page is generated from live Sleeper data by the tooling in a separate
private repo; this repo holds only the rendered result.

`noindex` is set — the page is reachable by link but is not meant to turn up
in search results.
