# WC26 Predictor — FIFA World Cup 2026 Live Fixture & Prediction App

A single-file, mobile-first web app. No build step, no server, no cost.

## Deploy free on GitHub Pages (~3 minutes)

1. Create a free account at github.com (skip if you have one).
2. Click **+ → New repository**, name it `wc26`, set it **Public**, click **Create**.
3. On the repo page click **uploading an existing file**, drag in `index.html`, click **Commit changes**.
4. Go to **Settings → Pages**, under *Branch* pick `main` and `/ (root)`, click **Save**.
5. After ~1 minute your app is live at `https://YOUR-USERNAME.github.io/wc26/`.

On your phone, open that URL → browser menu → **Add to Home Screen**. It now looks and feels like a native app.

To update the app later, just upload a new `index.html` over the old one.

## Live scores — 4 free sources, freshest wins

- **ESPN public scoreboard (automatic, no signup):** minute-by-minute live scores polled every 90s during match windows.
- **ESPN public match summary (automatic, no signup):** goal timeline, scorer names, assist info, and interactive lineups with public player headshots or jersey images when available.
- **fixturedownload.com feed (automatic):** full schedule, confirmed results, knockout matchups as groups finish.
- **football-data.org (optional free key):** backup live source incl. penalty-shootout winners — paste token under **More → Live data**.
- **Google News scanner:** open any team → "Scan latest news" pulls live headlines, flags injury/availability signals and suggests a one-tap rating adjustment.
- **Manual override:** watching the game? Enter the score yourself — online full-time results reconcile automatically later.

## How predictions work

Base team ratings calibrated to FIFA rankings (June 2026) → live Elo updates after every real result (K=40, margin-weighted) → tournament form (±36) → host-nation edge (+45 in own country) → your news adjustments (±100 per team, set via slider after reading linked headlines). Win/draw/loss probabilities from the rating gap; scorelines from a Poisson goal model; tournament odds from 2,000 Monte Carlo simulations including FIFA's third-place slot constraints and the full 32-team bracket.

## Features

New in this version: live match sheets now include scorer timelines, goal times, and interactive lineups fed by ESPN's public match summary.

Matches by day with live scores and confidence bars · live + AI-projected group tables · tappable knockout bracket (your picks vs AI) · tournament simulator with title odds · You-vs-AI prediction game with points · per-team news sliders and injury news links · dark mode · works offline after first load (picks and data persist on your device).

Unofficial fan app, not affiliated with FIFA.
