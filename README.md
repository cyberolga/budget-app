# Weekly budget app

**[Live demo →](https://cyberolga.github.io/budget-app/)** (open on your phone; the interface is in Polish)

<img src="https://raw.githubusercontent.com/cyberolga/cyberolga/main/screenshots/budget.jpg" alt="Screenshot of the budget app" width="320">

I built this app for my mum. She wanted something simpler than a spreadsheet: type what you bought, see how much is left.

## How it works

- Type a purchase in plain words, e.g. `chleb i mleko 12,50` (bread and milk 12.50). The app reads the amount and guesses the category (groceries, pharmacy, transport…) from the words.
- Each category has a weekly limit; bars turn amber near the limit and brick red when it is exceeded.
- The top of the screen shows what is left for the week and roughly how much that is per day.
- Weekly or monthly budget, large readable type, light mode by day and dark mode at night.
- Data stays on the phone (browser storage), with a copy-and-paste backup.

## Android version

The same app is packaged as an Android `.apk` with a thin WebView wrapper and built automatically by GitHub Actions on every push. That repository is private because it contains the signing key.

## Tech

Single HTML file, plain JavaScript, no libraries, no server.

---
Made by [Olga Hsieh](https://github.com/cyberolga).
