# Names Still Growing: Many Names, Children 0–18

A memorial data visualization displaying the names and ages of children (ages 0–18) killed in Gaza, based on official Ministry of Health records.

## Data Source
- **Source**: [Airwars - Ministry of Health Gaza List](https://airwars.org/moh-list/)
- **Documentation**: [Airwars Explanation & Methodology](https://airwars.org/moh-list/)
- **Series**: Part 1 of 30 (Full Roll)

## About This Project
This repository contains a single-page HTML memorial that cycles through approximately **19,771 names**, displaying:
- Name in Arabic (original)
- Name in English (transliterated)
- Age at time of death

The visualization uses a minimalist, reverent design with a slow fade animation (5-second intervals) to allow each name to be seen individually.

## How to View
Since the dataset is large (19k+ records), GitHub cannot render the preview directly.

**Live Version**: [Enable GitHub Pages](https://pages.github.com/) in your repository settings to serve the HTML file.

**Local View**: Download `names-still-growing.html` and open it in any modern web browser.

## Technical Details
- **Format**: Single-file HTML5 with embedded CSS/JavaScript
- **Data**: JSON array embedded in vanilla JavaScript (no external dependencies)
- **Language**: Arabic (RTL) with English transliterations
- **Animation**: CSS fade transitions, auto-advancing every 5 seconds

## Context
This data represents the Ministry of Health Gaza's official list of fatalities under age 18. For full context on data collection methodology, verification processes, and updates, please refer to the [Airwars methodology page](https://airwars.org/moh-list/).

---

*This is a memorial project intended to humanize statistical data. Each number represents an individual life.*
