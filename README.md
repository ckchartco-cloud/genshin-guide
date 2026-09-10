# Genshin Guide

A simple, mobile-friendly fan companion for planning Genshin Impact character builds, teams, and farming goals.

## Current starter version

- Character roster with local “owned” tracking
- Complete character roster loaded from a maintained fan-made data API
- Real character portraits with a fallback when an image is unavailable
- Character build summaries
- Larger character portraits with compact Guide/Add controls
- Inline expandable guides under each character card
- Compact card layout with larger portraits and right-aligned actions
- English / Chinese interface switch
- Search, ownership, element, role, tier, and 4-star/5-star filters
- Account-value tiers based on C0/general use, with an Unrated fallback
- Team suggestions ranked by how many owned characters fit each team
- Inventory and artifact assignment tab with GOOD/JSON import
- A farm-next column showing the first missing artifact direction
- Farm-planning checklist
- Responsive layout that works on iPhone and GitHub Pages

The app is intentionally dependency-free: open `index.html` directly or publish the repository with GitHub Pages. The roster uses the public `genshin.jmp.blue` API at runtime; if that service is unavailable, the app keeps the starter roster available.

## Inventory import

Open the **Items** tab and choose a GOOD/JSON export from a compatible inventory scanner. The app stores the imported file in the browser's local storage and uses it to suggest a weapon and artifact for each owned character. It does not connect to HoYoverse accounts and never asks for a game login or password.

The assignment is a practical starting point, not an automatic optimizer: weapon type, level, rarity, artifact set name, and available character guide data are used first. Always confirm the final build, main stats, substats, constellations, and current patch changes in-game. Character tier labels are heuristic guide filters, not official rankings.

## Tiers and language

The tier filter is an account-value guide for general C0 use, not a promise of damage or an official HoYoverse ranking. Genshin teams are highly context-dependent, so characters without curated starter guidance remain Unrated. Use the language selector in the top-right corner to switch between English and Simplified Chinese.

## Important note

This is an unofficial fan project. The included guide data is starter/sample data and should be reviewed against the current game patch before use. Genshin Impact and its characters belong to HoYoverse.
