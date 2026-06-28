# Right Hand Studio — Website (deploy folder)

Static site. No build step. Deploy this whole `rhs-site/` folder.

## Image mapping (top-to-bottom, per your selection in "images 2")
1 → Hero (marble table + curtains)      = uploads/hero.png
2 → Intro (hands on laptop)             = uploads/intro.jpg
3 → Band (woman from behind, window)    = uploads/band.png
4 → Who-for (chair + notebook)          = uploads/who-for.png
5 → Founders (the two founders)         = uploads/founders.png
6 → Apply (blazer + stylus)             = uploads/apply.png
Eric avatar (framed to face)            = uploads/eric.png
Agustin avatar                          = uploads/agustin.png

## Links / behavior (as designed)
- "Start the conversation" (nav + apply) → Calendly
- Morning Brief → not clickable ("coming soon")
- FAQ → on-page accordion
- Forms → Formspree (price xdavgwaw, apply maqzopnl, newsletter mqeoqyew)

## Run locally
cd rhs-site && python3 -m http.server 8000  → http://localhost:8000

## Deploy
Drag this folder onto Netlify Drop (app.netlify.com/drop), or any static host.
