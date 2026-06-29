# The AI Spend Cap Tracker

A neutral, sourced, public record of organizations capping, cutting, or centralizing **employee AI-coding spend** — the 2026 shift from "use AI as much as possible" to rationing ("tokenmaxxing → tokenminimizing").

Every entry in the table below is backed by a named source. Spotted one we're missing? See [CONTRIBUTING](CONTRIBUTING.md).

## Tracker

| Company | What they did | Figure | Date | Tool(s) | Source(s) |
|---|---|---|---|---|---|
| **Uber** | Per-employee monthly cap on AI coding-tool spend (per tool; exceedable with approval), after exhausting its 2026 AI budget in ~4 months. | $1,500 / month per tool | Jun 2026 | Cursor, Claude Code | [Bloomberg](https://www.bloomberg.com/news/articles/2026-06-02/uber-caps-usage-of-ai-tools-like-claude-code-to-cut-costs) · [TechCrunch](https://techcrunch.com/2026/06/02/uber-caps-employee-ai-spending-after-blowing-through-budget-in-four-months/) · [Yahoo Finance](https://finance.yahoo.com/sectors/technology/articles/uber-caps-monthly-employee-ai-180342247.html) |
| **Microsoft** | Cancelling internal Claude Code licenses in the Experiences + Devices division; engineers moved to GitHub Copilot CLI. | Reported ~$500–$2,000 / engineer / month | by 30 Jun 2026 | Claude Code → GitHub Copilot CLI | [Windows Central](https://www.windowscentral.com/microsoft/microsoft-cancels-claude-code-licenses-shifting-developers-to-github-copilot-cli-a-move-likely-driven-by-financial-motives) · [TechRadar](https://www.techradar.com/pro/microsoft-may-discontinue-claude-code-internally-as-it-looks-to-push-users-towards-github-copilot) |

## Candidate entries — unverified (NOT cited until sourced)
- **Meta** — reportedly centralizing usage via an internal "AI gateway." [VERIFY]
- **Amazon** — reported tightening of AI-coding spend. [VERIFY]
- **Walmart** — reported internal cap. [VERIFY]
- **AT&T** — reported Copilot usage limits. [VERIFY]

## Inclusion rule
An organization is listed in the table only with a **named, linkable source** (reputable outlet or first-party statement). Record the mechanism precisely (per-tool dollar cap vs license cancellation vs centralization). Unconfirmed leads stay in "Candidate entries" marked [VERIFY]. Figures change — re-check periodically.

## Why this exists
A spend cap is a blunt instrument: it throttles an organization's highest-leverage engineers and does nothing about proprietary code leaving for third-party models. The structural alternative is **routing, not rationing** — a layer that sends only what's worth it to a premium model and keeps sensitive work local. A reference implementation of that pattern is [Switchboard](https://github.com/aivinay/switchboard) (MIT; reproducible benchmark, [DOI](https://doi.org/10.5281/zenodo.20836918)).

## License
Data licensed under CC BY 4.0. Contributions welcome.
