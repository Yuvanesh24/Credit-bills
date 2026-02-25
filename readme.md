# Credit Bill — Patient Travel & Others

A simple, offline-first web app to track patient visit travel costs and other bills. Built with plain HTML, CSS, and JavaScript — no installation needed.

## Features

- **Patient Tab** — Add patients once, log multiple visits under each with date, transport, passengers, and cost
- **Others Tab** — Track therapist travel, office supplies, or any other bills separately
- **Combined Total** — See the grand total of both patients and others at a glance
- **Cost by Patient Chart** — Visual bar chart with View All support
- **Per-patient CSV Export** — Download a bill summary for any individual patient
- **Full CSV & JSON Export** — Export all data for records or backups
- **Import** — Restore data from a previously exported JSON file
- **Works offline** — No internet required after first load (except for Google Fonts)
- **Auto-save** — All data is saved automatically in your browser

## How to Use

1. Open the site in your browser
2. Go to the **Patients** tab and click **Add Patient** to create a patient
3. Click **View ▾** on any patient to expand their visits
4. Click **+ Add Visit** to log a date, transport mode, passengers, and cost
5. Use the **Others** tab for therapist travel or any non-patient bills
6. Use **↓ CSV** inside a patient's panel to download their individual bill
7. Use **↓ JSON** regularly to back up all your data

## Data & Storage

All data is stored in your **browser's localStorage**. This means:

- Data is saved automatically as you work
- Closing and reopening the browser keeps your data intact
- Data is **device and browser specific** — it won't sync across devices
- Clearing browser cache will erase data — export a JSON backup regularly

## Tech Stack

- HTML + CSS + Vanilla JavaScript
- Google Fonts (Cormorant Garamond, Outfit, DM Mono, Syne)
- No frameworks, no dependencies, no backend

## License

Personal use.