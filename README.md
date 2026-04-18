# sky's calc

A simple web-based calculator to track progress and stats for game grinding. It estimates how long it’ll take to hit a target based on your current multipliers and gains.

### Features
* **Precise Math:** Uses `Decimal.js` to handle huge numbers (M, B, T, etc.) without breaking.
* **Auto-Upgrade Logic:** Calculates if it’s faster to save up for a new multiplier or just keep grinding.
* **Quest Tracking:** Includes daily and weekly token bonuses in the time estimate.
* **Clean UI:** Dark mode layout that works on mobile and desktop.

### How it works
Enter your current stats and target, select your multiplier, and the script runs a loop to find the most efficient path to your goal. It accounts for the time spent waiting for tokens to buy upgrades versus the time gained from the increased stats.
