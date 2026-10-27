# Day by Day — Goal Calendar

A local-first annual goal tracker. Set one goal for the year, mark completed
days, and keep an eye on your streak and progress.

## Run locally

Serve this directory with any static file server and open `goal-calendar.html`.
For example:

```sh
python -m http.server 8000
```

The goal and completed days are stored in browser local storage, separately for
each year. No account or backend is required.

## Deploy to Vercel

Import `jonathanbgjo/Goal-Calendar` as a new project in Vercel. Use the `Other`
framework preset, with no build command or output directory. Vercel serves the
static files directly, and `vercel.json` routes the domain root to the calendar.
