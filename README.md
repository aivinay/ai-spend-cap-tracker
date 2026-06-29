# The AI Spend Cap Tracker

A neutral, sourced, public record of organizations capping, cutting, or centralizing **employee AI-coding spend** — the 2026 shift from "use AI as much as possible" to rationing ("tokenmaxxing → tokenminimizing").

**Last updated:** 28 Jun 2026

Every entry in the table below is backed by a named source. Spotted one we're missing? See [CONTRIBUTING](CONTRIBUTING.md).

## Tracker

| Company | What they did | Figure | Date | Tool(s) | Source(s) |
|---|---|---|---|---|---|
| **Uber** | Per-employee monthly cap on agentic AI coding spend (per tool; exceedable with approval), after exhausting its 2026 AI budget in ~4 months. | $1,500 / month per tool | Jun 2026 | Cursor, Claude Code | [Bloomberg](https://www.bloomberg.com/news/articles/2026-06-02/uber-caps-usage-of-ai-tools-like-claude-code-to-cut-costs) · [TechCrunch](https://techcrunch.com/2026/06/02/uber-caps-employee-ai-spending-after-blowing-through-budget-in-four-months/) |
| **Microsoft** | Cancelling internal Claude Code licenses in the Experiences + Devices division; engineers moved to GitHub Copilot CLI. | Reported ~$500–$2,000 / engineer / month | by 30 Jun 2026 | Claude Code → GitHub Copilot CLI | [Windows Central](https://www.windowscentral.com/microsoft/microsoft-cancels-claude-code-licenses-shifting-developers-to-github-copilot-cli-a-move-likely-driven-by-financial-motives) · [TechRadar](https://www.techradar.com/pro/microsoft-may-discontinue-claude-code-internally-as-it-looks-to-push-users-towards-github-copilot) |
| **Meta** | Capping employee AI token usage with real-time spend tracking via a new "AI Gateway" dashboard; dismantled its "Claudeonomics" usage leaderboard (73.7T tokens in ~30 days, 85k+ employees) and is nudging staff to in-house MetaCode over Claude, with internal AI cost tracking toward "billions" in 2026. | Per-employee token caps; costs "approaching billions" | Apr–Jun 2026 | Claude → in-house MetaCode ("AI Gateway") | [Fortune](https://fortune.com/2026/04/09/meta-killed-employee-ai-token-dashboard/) · [The Next Web](https://thenextweb.com/news/tokenminimizing-companies-cap-employee-ai-spending) |
| **Walmart** | Replaced unlimited token usage with a set per-employee token allowance on its in-house "Code Puppy" AI agent after demand outran budget (announced by Global CTO Suresh Kumar). | Per-employee token allowance (previously unlimited; exact figure undisclosed) | Jun 2026 | Code Puppy (in-house) | [Bloomberg](https://www.bloomberg.com/news/articles/2026-06-01/walmart-caps-usage-of-an-ai-tool-for-employees-after-high-demand) · [Arkansas Democrat-Gazette](https://www.arkansasonline.com/news/2026/jun/02/walmart-puts-leash-on-employee-code-puppy-ai-use/) |
| **AT&T** | Began limiting some employees' access to GitHub Copilot amid rising AI-tooling costs. | Access limits for certain staff (exact cap undisclosed) | Jun 2026 | GitHub Copilot | [The Next Web](https://thenextweb.com/news/tokenminimizing-companies-cap-employee-ai-spending) · [GuruFocus](https://www.gurufocus.com/news/8920359/att-limits-ai-tool-usage-amid-rising-costs) |

## Counter-examples / reversals

- **Amazon** — earlier restricted Claude Code, but after internal developer pushback (a ~1,500-endorsement employee thread) **expanded** access to external agentic tools (Claude Code + Codex, on Bedrock) company-wide in May 2026, beyond its in-house Kiro — currently loosening, not capping. Sources: [Futurism](https://futurism.com/artificial-intelligence/amazon-kiro-coding) · [The New Stack](https://thenewstack.io/amazon-coding-agents-developers/)

## Inclusion rule
An organization is listed in the table only with a **named, linkable source** (reputable outlet or first-party statement). Record the mechanism precisely (per-tool dollar cap vs license cancellation vs centralization). Unconfirmed leads stay in "Candidate entries" marked [VERIFY]. Figures change — re-check periodically.

## Why this exists
A spend cap is a blunt instrument: it throttles an organization's highest-leverage engineers and does nothing about proprietary code leaving for third-party models. The structural alternative is **routing, not rationing** — a layer that sends only what's worth it to a premium model and keeps sensitive work local. A reference implementation of that pattern is [Switchboard](https://github.com/aivinay/switchboard) (MIT; reproducible benchmark, [DOI](https://doi.org/10.5281/zenodo.20836918)).

## License
Data licensed under CC BY 4.0. Contributions welcome.
