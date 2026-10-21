# Route landing: wireframe

Wireframe for the new [route.fun](https://www.route.fun) landing page. Single static file, no build step. Light mode, Route tokens, same style as [route-chat](https://github.com/todels/route-chat) and [route-earn](https://github.com/todels/route-earn).

**Local:** `python3 -m http.server 5204 -d .` then open http://localhost:5204

The button at the bottom right toggles the wireframe notes on and off. Animations are rough motion ideas, not final.

## Sections (from the client brief)

| # | Section | What's in it |
|---|---------|--------------|
| 01 | Hero | Swap card as hero, stripped to amount + two tokens + one button at rest. Typing an amount reveals dollar values, a short "checking pools" beat, then rate, route and the Kyber edge. No background graphic. |
| 02 | How Route works | Four steps beside an isometric route graph: tokens as vertices, pools as edges. Scan lights edges outward from ETH, Split lifts the vertices on the three best paths like map pins, Check ticks each hop, Sign lands in NVDA. Motion idea, final illustration to be designed. |
| 03 | Onchain markets | No charts. Two moving rows of stocks and ETFs/gold, then one big "+$X more than Kyber" number beside a minimal head-to-head that races into order. Click any asset to compare it. |
| 04 | Builders | Feature list on the left drives the code panel on the right: quote, live streaming log, zap legs, partner fee calculator wired into the code. Placeholder logo row. |
| 05 | Coverage by chain | Three columns by how much of Route runs there: everything (Robinhood Chain), swaps (Arc), screener data (nine more chains). |
| 06 | Close | Big wordmark, tagline, Launch app, footer. Not in the brief. |

## Sources

Stats, case study numbers, API shape and builder fee cap (50 bps) are from docs.route.fun and route.fun/analytics (Oct 2026). Stock prices are samples from route.fun/yield. Streaming quotes and the non-Robinhood chains are flagged in the page as "confirm".
