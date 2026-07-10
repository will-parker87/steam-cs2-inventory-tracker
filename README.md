# Steam Inventory Tracker v2026 - inventory tracker 2026

> **Follow CS2 Steam inventory value through time with a local web dashboard, market pricing, and built-in history views in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/will-parker87/steam-cs2-inventory-tracker?style=flat-square)](https://github.com/will-parker87/steam-cs2-inventory-tracker)

---

<p align="center">
  <a href="https://will-parker87.github.io/steam-cs2-inventory-tracker/">
    <img src="https://img.shields.io/badge/Download-Steam%20Inventory%20Tracker%20Latest-brightgreen?style=for-the-badge" alt="Download Steam Inventory Tracker">
  </a>
</p>

> **[Direct Download - Steam Inventory Tracker v2026](https://will-parker87.github.io/steam-cs2-inventory-tracker/)**

---

[Download Latest Build](https://will-parker87.github.io/steam-cs2-inventory-tracker/)

---

## Overview

Steam Inventory Tracker is a browser-based utility for keeping tabs on CS2 inventory value and how it evolves over time. It combines inventory records with Steam Market pricing so you can inspect current totals, individual items, and historical movement from a single interface.

The app centers on a local, portfolio-like dashboard that is straightforward to browse and filter. It is a strong fit for anyone who wants a more organized view of item value, account totals, and price history without switching between spreadsheets and market pages.

---

## Capabilities

- Monitors CS2 Steam inventory value over time
- Collects inventory data together with Steam Market prices
- Keeps daily history for totals, accounts, and single items
- Shows a local portfolio-style market dashboard
- Offers search and filtering by type, exterior, rarity, and account
- Supports alternate price bases and both table and card layouts
- Provides historical value charts with event markers
- Exports to CSV and includes market-link copy actions

---

## Installation

Clone the repo or download the project files, then open the web app from the project directory.

1. Get the source:
   - `git clone https://github.com/will-parker87/steam-cs2-inventory-tracker.git
   - or download the repository as a ZIP and extract it
2. Open the local site in your browser using the project entry file
3. If you are serving it locally, launch it with your preferred static web server

Example:
- `cd steam-inventory-tracker`
- start your local web server
- open the app URL in your browser

---

## How to Use

1. Load your inventory data into the tracker
2. Let the app fetch or refresh Steam Market pricing
3. Review the dashboard for current totals and item breakdowns
4. Use filters to narrow results by account, rarity, exterior, or item type
5. Switch between table and card views depending on how you want to inspect holdings
6. Compare historical charts to see value changes across time
7. Export the results to CSV when you need a spreadsheet-friendly snapshot
8. Copy market links for fast access to items on the market

---

## Configuration

Most behavior is controlled through the app flow and the local files used by the tracker. If you tailor the project, keep the inventory source, price source, and export paths aligned with your setup.

Example configuration shape:

{
  "inventorySource": "local",
  "priceSource": "steam_market",
  "historyTracking": true,
  "exports": {
    "csv": true
  },
  "viewMode": "dashboard"
}

---

## Requirements

- Web browser
- Local environment for hosting or opening the project
- Access to Steam inventory data
- Access to Steam Market pricing data
- Storage for saved history, charts, and CSV exports

---

## FAQ

**How do I update the tracker?**  
Swap in the latest repository files locally or rebuild from current source, depending on how you host the project.

**Where is the data stored?**  
History, exports, and dashboard data live in the local project files or whatever storage layer your setup uses.

**Can I change the way values are shown?**  
Yes. The dashboard supports alternate price bases and multiple presentation styles, including table and card views.

**What should I do if prices do not appear?**  
Verify that your inventory source is available, the market data endpoint can be reached, and your local setup is loading fresh data.

**Does it support multiple accounts?**  
Yes. The tracker includes account-level history and filtering so you can review holdings across accounts.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
