# WC2026 Fantasy — Live Tracker

Live leaderboard and match tracker for our 2026 World Cup Fantasy League
(12 players, 2 rooms, 8 teams each).

The page fetches live scores from ESPN's public scoreboard API directly in the
browser, so it updates itself — no manual score entry, no scheduled jobs.
It refreshes every minute while games are live.

Scoring: Win = 2 · Draw = 1 · OT/pens loss = 1 · Loss = 0

A snapshot of results is baked into `index.html` as a fallback in case the
live feed is ever unreachable.
