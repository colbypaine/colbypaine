# Hi, I'm Colby 👋

**Wealth management meets AI.** Ex-J.P. Morgan (Client Associate → Senior Client Associate), Series 7 / 66 exam holder, SF native, surfer, former D1 water polo player.

I build small tools that handle the repetitive parts of wealth management, test trading ideas against real market data, and turn the rest of my life (surf sessions, travel stories, books) into artifacts I can keep.

---

## 🏦 Wealth management workflows
Six Streamlit apps for jobs a private wealth team usually does by hand. They all run on made-up clients. No real client data anywhere.

| App | What it does |
|---|---|
| **Drift Monitor** | Checks each household against its guardrails (20% single-stock cap, stock/bond bands, cash floor, loan-to-value on stock-backed credit lines) and replays past market crashes |
| **Recurring Distribution Finder** | Spots client patterns who keep asking for cash, offers a monthly transfer, and gives the advisor five one-click ways to raise it |
| **Credit Line Finder** | Finds clients who pre-qualify for a securities-based line of credit and runs the paperwork through to an open line |
| **RMD Tracker** | Tracks required minimum distributions across every IRA and drafts each client's reminder email |
| **KYC Tracker** | Runs KYC refresh timers (every 3 years, or yearly for higher-risk clients) with a one-click check-in email |
| **Deposit Screener** | Flags idle cash, business activity in personal accounts and private bank candidates, then drafts the referral for cross business |

## 📈 Quant research
Python backtests built on yfinance, OpenInsider and SEC EDGAR data, each measured against simply holding SPY.

| Project | What it tests | Status |
|---|---|---|
| **Backtest Runner** | A reusable pipeline: pick a universe, define a signal, set the rules, get charts and a written report | ✅ In use |
| **Golden Cross** | The 50-day / 200-day
