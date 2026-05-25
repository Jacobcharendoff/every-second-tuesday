# Every Second Tuesday

Toronto party rock band. We jam on Tuesdays so your Saturdays don't suck.

## Stack

Single-page static site. No build step. Drop `index.html` on any host and it works.

- `index.html` — the entire site (HTML, CSS, JS inlined)
- `gigs.json` — upcoming gig data, read by the hero ticker on page load
- `assets/hero-placeholder.mp4` — looping background video for hero
- `assets/audio/preview-*.mp3` — song preview clips played by the persistent mini-player

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000

## Deploy

Connected to Vercel. Push to `main` ships to production.

## Booking

booking@everysecondtuesday.ca
