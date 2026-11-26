# Charting Habits

Charting Habits is an offline habit tracker you can run from a single HTML file. Log a completion with one click. The chart rises when you make progress and stays flat on days you skip.

[Download the app](https://github.com/PearceMullins/charting-habits/releases/latest/download/Charting-Habits.html) · [View the latest release](https://github.com/PearceMullins/charting-habits/releases/latest)

![Charting Habits showing a 30-day line chart with sample habits and a selected date](docs/tracker.png)

## Get started

1. Download the HTML file and open it in a modern browser. No account, server, or installation is needed.
2. Select **New habit**. Choose one completion per day or a counter with an optional daily limit.
3. Select **Log today** to record progress. Select an earlier date on the chart or use the date field to add or remove a completion. **Undo** reverses the last log change.

## What you can do

- **See progress.** Switch between a step line, a line with dots, daily bars, weekly bars, and monthly comparison. Track streaks, days logged this month, and progress toward a weekly goal.
- **View habits together.** Use **Overview** for small charts or **Compare habits** for one combined chart. Change **Days shown** to set the range for both views.
- **Choose your colors.** The default theme is black and blue. Use **Theme** to change the background and accent, and set each habit's chart color in **Edit habit**. Use the color pickers or paste a hex code.
- **Share a chart.** **Export chart** saves a 30-day PNG for the current habit.

## Saving and backups

The app saves habits, history, and settings in the browser when it supports storage for local files. It makes no network requests. Moving or renaming the HTML file, changing browsers, or clearing browser data can make the history unavailable in that copy.

- **Back up:** Select **Data → Export backup** to download a JSON file with your habits, history, and settings.
- **Move or restore:** Open the HTML file in the new location or browser. Select **Data → Restore backup** and choose your JSON file. The app asks before replacing existing data.
- **Start fresh:** Export any history you want to keep, then clear the browser's saved site data for the file. Removing the HTML file alone may leave saved history in the browser.

If the app shows that automatic saving is unavailable, export a backup before closing it.

## Source

[Charting Habits.html](Charting%20Habits.html) contains the interface, charts, and storage logic. To work on the app, edit the file and reload it in your browser. No build step is required.
