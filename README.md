# Game Tracker Spreadsheet

A lightweight, browser-based utility for managing game libraries and play sessions. Designed for offline use and maximum portability via a single-file architecture.

### Quick Start
Open `tracker.html` in any modern web browser. Use the sidebar to log games and utilize the **Export/Import** buttons to manage your data backups via JSON.

---

## Key Features
* **Local Persistence:** Data is stored locally in the browser; no account or internet connection required.
* **Data Portability:** Complete JSON export and import functionality for manual backups and cross-device migration.
* **Dynamic UI:** Includes real-time search filtering, table sorting, and multiple visual themes.
* **Session Tracking:** Precise playtime logging with decimal support and status categorization.

## Technical Specifications
* **Architecture:** Single-file HTML5/CSS3/JavaScript.
* **Storage:** Browser `localStorage` API.
* **Dependencies:** Zero (No external libraries or frameworks).
* **Data Format:** JSON.

## Usage & Backups
* **Saving:** Entries are saved to the browser cache immediately upon submission.
* **Backups:** Use the **Export** function regularly. This generates a `games.json` file which can be moved across devices or folders.
* **Restoration:** Use the **Import** tool to reload your library from a saved JSON file.

## Known Limitations
> [!IMPORTANT]
> **Data Persistence:** Because this tool uses `localStorage`, your data is tied to the specific browser and device you are using. Clearing your browser cookies/cache or using "Incognito Mode" may delete your entries. Always maintain a recent JSON export as a master backup.
