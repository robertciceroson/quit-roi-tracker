# Quit ROI Tracker

A web app that turns quitting smoking or drinking into a personal return-on-investment statement: money kept, hours reclaimed, and health milestones reached.

This is the **user-testing version**. It runs entirely in the browser as a single `index.html` file, with no server, build step or account.

## Features

- **Setup:** cigarettes, alcohol or both; 2026 state-average pack prices or your own price; packs or drinks per day; quit date; hidden monthly costs; a named savings goal
- **Today:** money kept, dollars per day and per year, hours back, cravings beaten, goal progress, next health milestone
- **Craving coach:** a 60-second guided breathing timer, then log "I beat it" or "I slipped"
- **Slips without shame:** a slip restarts the streak but keeps lifetime savings
- **Health:** a smoking-recovery milestone timeline with countdowns
- **History:** every craving and slip, with optional triggers, plus free support lines
- **Weekly ROI statement:** this week's return and the projected 1-year return
- **Tester tools:** a task checklist, skip-ahead time controls, and a feedback form that produces copyable text

## Run it locally

Download `index.html` and open it in any modern browser.

## Deploy to GitHub Pages

1. Create a new public repository on GitHub, for example `quit-roi-tracker`.
2. Upload `index.html` and this `README.md` to the repository root and commit to `main`.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
5. After a minute or two the site is live at `https://<your-username>.github.io/quit-roi-tracker/`.

Optional: add a custom domain in the same Pages settings.

To update the app, commit a new `index.html`; Pages redeploys automatically.

## Privacy

All data stays in the tester's own browser (`localStorage`). Nothing is sent to a server, and clearing site data or using a private window resets the app. Feedback is shared only when a tester copies it and emails it.

## Data and assumptions

- Pack prices: 2026 state averages from [World Population Review](https://worldpopulationreview.com/state-rankings/cigarette-prices-by-state) (U.S. $10.15, Missouri $8.01, California $11.78, New York $14.83). Testers can enter their own price.
- Hours back: estimated at 6 minutes per cigarette (20 per pack) and 15 minutes per drink.
- A slip subtracts one day of the tester's usual spend.
- Health milestones are draft copy based on widely published CDC and American Cancer Society timelines. Confirm the wording and cite each item before a public launch.

## Disclaimer

This app provides general information and motivation. It is not medical advice. Anyone who drinks heavily every day should talk to a doctor before stopping.

Support: Quitline 1-800-QUIT-NOW (1-800-784-8669) · SAMHSA National Helpline 1-800-662-4357

## Feedback

Testers: use the **Test** tab, then send your copied feedback to rson226@gmail.com.

## Author

Robert Son · [github.com/robertciceroson](https://github.com/robertciceroson)
