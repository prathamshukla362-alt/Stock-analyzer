# Stock Analyzer & Risk

A mobile-friendly stock analyzer that scores companies on fundamentals and risk, with charts. It runs entirely in the browser as a single HTML file. No build step, no server, no install.

**Live site:** https://&lt;your-username&gt;.github.io/&lt;repo-name&gt;/

## Features

- **Dashboard:** Gauges for average fundamentals and risk, a risk distribution donut chart, a fundamentals-vs-risk scatter plot, and top-fundamentals bars.
- **Watchlist:** Sample stocks as cards with fundamentals and risk bars, filterable by Low, Moderate, and High risk.
- **Lookup:** Search any ticker covered by Financial Modeling Prep (requires a free API key).
- **Stock detail:** Fundamentals and risk gauges, a six-axis radar chart, 52-week price range, metric tables, and plain-language risk explanations.
- **History:** Live lookups from the current session, with a fundamentals bar chart.
- **Settings:** API key entry and appearance (Dark, Light, or System).
- **Source labels:** Live metrics show the provider and retrieval time. Missing values show "Not available" instead of a guess.

## Quick start

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

The watchlist works immediately with built-in sample data.

## Live data (optional)

Live lookups use [Financial Modeling Prep](https://financialmodelingprep.com/):

1. Create a free account and copy your API key from the dashboard.
2. Open the app, go to **Settings**, paste the key, and tap **Use this key**.
3. Go to **Lookup** and enter a ticker such as `AAPL`.

The key is held in memory for the current session only. It is never written to the file or to browser storage.

**Do not commit your API key to this repository.**

## Deploy with GitHub Pages

1. Upload `index.html` to the top level of the repository (not inside a folder).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Open the URL GitHub shows, usually `https://<your-username>.github.io/<repo-name>/`.

On a phone, open that URL and use **Add to Home Screen** to install it like an app.

## Project structure

```
index.html    The whole app (HTML, CSS, JavaScript, charts)
README.md     This file
LICENSE       MIT license
.gitignore    Files Git should ignore
```

## Disclaimer

Sample data is for illustration only. Live data comes from third-party providers and may be delayed or incomplete. Scores are simple rule-based indicators, not investment advice. Verify figures with the original source before making any investment decision.

## License

MIT. See `LICENSE`.

