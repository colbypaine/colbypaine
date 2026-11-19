# Hi, I'm Colby 👋

Ex-J.P. Morgan private wealth (The Alta Group, San Francisco's #1 high-net-worth team) · Series 7 & 66 qualified. I build AI tools for advisors and the clients they serve, mostly in Claude Code and Codex. Everything below lives at **[colbypaine.com](https://colbypaine.com)**.

---

## 🏦 Advisor Workstation
Nine browser tools for jobs a private wealth team usually does by hand. **[Try it at colbypaine.com/workstation.html](https://colbypaine.com/workstation.html)**: no login, no install. Everything runs on made-up clients. No real client data anywhere. Six of the tools also have Python / Streamlit versions.

| Tool | What it does |
|---|---|
| **[Client Book](https://colbypaine.com/workstation.html#clients)** | A household view of 50 fictional accounts across 13 households (joint, trust, IRA, Roth, UTMA), with a touchpoint radar that drafts personal check-ins |
| **[Meeting Loop](https://colbypaine.com/workstation.html#meeting)** | Builds a one-page client brief before a review, then turns meeting notes into action items, CRM task drafts and a follow-up email |
| **[Concentrated Stock Strategist](https://colbypaine.com/workstation.html#stock)** | Compares five strategies for a concentrated position (sell, hold, covered call, collar, exchange fund) with tax math, 12-month stress tests and a SPY reference |
| **[Drift Monitor](https://colbypaine.com/workstation.html#drift)** | Checks each household against its guardrails (single-stock cap, stock/bond bands, cash floor, credit-line loan-to-value) and replays past market crashes |
| **[Distributions](https://colbypaine.com/workstation.html#distributions)** | Spots clients who keep asking for cash, proposes a monthly transfer and gives the advisor ways to raise it |
| **[Credit Lines](https://colbypaine.com/workstation.html#credit)** | Finds clients who pre-qualify for a securities-based line of credit and runs the paperwork through to an open line |
| **[RMD Tracker](https://colbypaine.com/workstation.html#rmd)** | Tracks required minimum distributions across every IRA, flags QCD candidates and drafts each client's reminder |
| **[KYC Tracker](https://colbypaine.com/workstation.html#kyc)** | Runs KYC refresh timers (every 3 years, or yearly for higher-risk clients) with a one-click check-in email |
| **[Deposit Screener](https://colbypaine.com/workstation.html#deposits)** | Flags idle cash, business activity in personal accounts and private bank candidates, then drafts the referral |

## 📈 Quant research
Python backtests built on yfinance, OpenInsider and SEC EDGAR data, each measured against simply holding SPY. **[Explore the research notebook](https://colbypaine.com/research.html)**: read the results, then change an assumption and rerun.

| Project | What it tests | Status |
|---|---|---|
| **Backtest Runner** | A reusable pipeline: pick a universe, define a signal, set the rules, get charts and a written report | ✅ In use |
| **Golden Cross** | The 50-day / 200-day moving-average crossover across a dozen large-cap stocks | ✅ Done |
| **Insider Buying** | Following $250K+ open-market insider purchases in the smallest S&P 500 companies, with and without a trailing stop | ✅ Done |
| **GGM Dividend Value** | Buying dividend stocks when a Gordon Growth Model valuation shows a margin of safety | ✅ Done |
| **Barbell** | "Silent execution" tech on one end, small/microcap value on the other, using point-in-time SEC fundamentals | 🔨 In progress |
| **Over Leveraged** | A short-only strategy targeting over-leveraged companies whose fundamentals are slipping | 🔨 In progress |

## 🛠️ Apps

| Project | What it is | Status |
|---|---|---|
| **[Echoes](https://echoes-journal.vercel.app/)** | An adaptive voice journal: an LLM writes a personal prompt, you answer out loud, and a follow-up question digs deeper. Electron desktop app on the OpenAI API, with a web preview | ✅ Web preview live |
| **[Throughline Careers](https://throughline-careers.vercel.app/)** | A career advisor for college students that starts with what makes them tick, not their résumé, then connects those interests to real roles. OpenAI API; co-built with a friend | ✅ Demo live |
| **Surf Journal** | Record a voice memo after a session; a watcher script transcribes it with Whisper and logs it to the journal. No typing | ✅ Working |
| **[colbypaine.com](https://colbypaine.com)** | My personal site, with two ways in: a project list and a 3D flight over San Francisco | ✅ Live |

## 🎨 Creative

| Project | What it is | How it's made |
|---|---|---|
| **[Fly in](https://colbypaine.com/fly.html)** | The site as a 3D flight over San Francisco, from the Marin Headlands to the waterfront | Three.js, built with Claude and Codex |
| **[Ferry Building Flyer](https://colbypaine.com/fork/creative/ferry-building-flyer/)** | Fly around Market Street and the Embarcadero; switch from sunset to a concert or a Giants parade, and call in a UFO | Three.js in the browser; [source](https://github.com/colbypaine/ferry-building-flyer) |
| **[Travel Visualizer](https://colbypaine.com/atht-globe.html)** | An interactive globe of my surf trip: nine countries, 22 flight legs, regional relief maps and a play-through tour | 3D globe in the browser, with privacy-rounded route data |
| **ATHT surf journals** | Magazine covers for four trip journals: Volume One, New Zealand, the Banyaks and the Mentawais | Generated in Codex, art-directed by me |
| **[Waveform visualizer](https://colbypaine.com/fork/creative/audio-viz/)** | Draws music, microphone input or a local file as 2D and 3D waveforms | Web Audio API in the browser |
| **[Slit-scan camera](https://colbypaine.com/fork/creative/slit-scan/)** | Combines slices from different moments into one image, live from your camera | Browser camera + canvas |
| **Book Synthesis** | Whole books condensed into 15-slide carousels you can read in five minutes | Python script that renders the slides · 🔨 Building |
| **Surf trip stories** | A memoir in progress from seven months chasing waves through Indonesia, New Zealand, Australia, Europe and Mexico | ✍️ Writing |

## 🤝 How I build
Claude is where things start: thinking out loud, brainstorming directions, shaping data and writing briefs. Codex does most of the heavy coding and all of the image generation, each experiment in its own branch. I give feedback by voice and typing while clicking through live builds, have the two tools audit each other, and review every merge myself.

## 🧰 Tools I use
Python · pandas · yfinance · Streamlit · matplotlib · Three.js · Whisper · Electron · OpenAI API · Claude Code · Codex · VS Code · Git

## 🌐 Find me
[colbypaine.com](https://colbypaine.com) · [LinkedIn](https://www.linkedin.com/in/colby-paine-349004179/)

---
_Everything here is for learning and research. Nothing is investment advice._
