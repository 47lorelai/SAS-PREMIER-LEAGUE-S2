# SAS Premier League Season 2 — Premium Live Web App

Static GitHub Pages app. Admin updates the published Google Sheet; the website reads the published CSV and refreshes every 30 seconds.

## Expected Google Sheet columns
MATCHDAY, HOME TEAM, AWAY TEAM, HOME SCORE, AWAY SCORE

## Deploy
Upload the contents of this folder to the root of a public GitHub repository, then enable Settings → Pages → Deploy from a branch → main → /(root).

The app is intentionally static and does not store Google account credentials.
