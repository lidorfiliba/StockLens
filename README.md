# 📊 StockLens — Financial Analyzer

A clean web app that combines two tools:
- **Stock Overview** — P/E, margins, dividends, valuation rating
- **Quarter Comparison** — Compare EPS & earnings between any two quarters

Built with plain HTML/CSS/JS. No backend needed. Uses [Alpha Vantage](https://www.alphavantage.co/) free API.

---

## 🚀 Deploy on GitHub Pages (5 minutes)

1. **Create a new GitHub repo** (e.g. `stocklens`)
2. Upload `index.html` to the repo root
3. Go to **Settings → Pages**
4. Under "Branch" select `main` and folder `/ (root)` → click **Save**
5. Your app is live at: `https://YOUR_USERNAME.github.io/stocklens`

---

## 🔑 API Key

The app uses a default demo key. For your own key:
1. Register free at [alphavantage.co](https://www.alphavantage.co/support/#api-key)
2. Paste your key into the "API Key" field at the top of the app

**Free tier:** 25 requests/day, 5/min.

---

## ⚠️ CORS Note

Alpha Vantage allows browser requests from most environments, but some networks may block them. If you get network errors, try:
- Opening the HTML file directly in your browser (not via VS Code Live Server)
- Deploying to GitHub Pages (recommended — works reliably)

---

## 📁 Files

```
index.html   ← entire app, single file, no dependencies
README.md
```
