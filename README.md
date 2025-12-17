# TIG:R Tierlist Backend

## Repository Purpose
This repository serves as the external backend for the tier list system used in the Roblox game  
**“Trollge Incident Game: Remastered”**.

The tier data is stored in JSON format and is fetched in-game using Roblox's `HttpService`.
The game periodically retrieves and caches the data to ensure up-to-date tier information
without requiring game updates.

## Data Files
- **tiers.json** — Main tier list file currently used in-game.
- **trolls.json** — Archived (previous troll tier data).
- **items.json** — Archived (previous item tier data).

Archived files are kept for reference and historical tracking but are not actively used.

## Notes
- This repository does not contain executable code.
- It only hosts structured tier data for in-game consumption.
- All data updates are controlled server-side within the game.

## Author
By **Nick_chill**
