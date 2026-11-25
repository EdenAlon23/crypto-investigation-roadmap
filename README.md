# Crypto Investigation Roadmap

An interactive study roadmap for blockchain investigation and crypto anti-money-laundering (AML), focused on the kind of work done by financial cybercrime investigators in Israel.

**Live site:** https://edenalon23.github.io/crypto-investigation-roadmap/

Built by **Eden Alon**, B.Sc. Computer Science student (cybersecurity track) at Holon Institute of Technology.

## What it is

A five-stage learning path that takes you from how blockchains work to how investigators trace and analyse illicit crypto flows:

1. **Fundamentals** – keys and addresses, the UTXO model vs. the account model, ERC-20 and TRC-20 tokens, stablecoins.
2. **Tracing** – clustering heuristics, peel chains, pass-through wallets, exchange attribution, bridges.
3. **Laundering** – placement, layering and integration on-chain, the FATF red flag indicators, sanctions lists, evidence integrity.
4. **Israeli casework** – public Israeli cases: crime-organization laundering, unlicensed crypto services, investment fraud, espionage paid in crypto, and the court rulings on freezing USDT held abroad.
5. **Data** – the public APIs (Etherscan V2, TronGrid, mempool.space), rate limits, and grounding an AI agent with tool use.

Every stage includes curated links (videos, papers, docs, case reports), a ready summary of each item, an illustrated chapter summary, a 6-question checkpoint quiz with explanations, and interview-style questions with model answers. A final summary ties everything into one investigation flow.

## Features

- Progress tracking per stage and overall, with a visual route
- Expandable summaries for all 45 study items
- Illustrated flow diagrams (inline SVG icons, responsive down to phone width)
- Graded quizzes with explanations and retry
- “Fast track” mode that shows only the core items
- One-click copy of all summaries as plain text
- Light and dark themes; no build step and no dependencies

## Tech

A single static `index.html`: semantic HTML, modern CSS (grid, `light-dark()`, `clamp()`), and vanilla JavaScript. Progress is kept in `localStorage`, so nothing leaves the browser.

## Run it locally

```bash
git clone https://github.com/EdenAlon23/crypto-investigation-roadmap.git
cd crypto-investigation-roadmap
python3 -m http.server 8000
# open http://localhost:8000
```

You can also just open `index.html` directly in a browser.

## Next step

This roadmap is the research phase for a planned project: a blockchain investigation workbench (.NET backend, TypeScript frontend) for case management, multi-chain tracing, FATF-based detection rules and evidence-grade reports.

## Disclaimer

An independent educational project built only from public sources. It is not affiliated with or endorsed by the Israel Police or any other agency. Links were checked in November 2026.

## License

MIT © 2026 Eden Alon
