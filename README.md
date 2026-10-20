# Route landing: wireframe

Wireframe for the new [route.fun](https://www.route.fun) landing page. Single static file, no build step. Light mode, Route tokens, same style as [route-chat](https://github.com/todels/route-chat) and [route-earn](https://github.com/todels/route-earn).

**Local:** `python3 -m http.server 5204 -d .` then open http://localhost:5204

The button at the bottom right toggles the wireframe notes on and off.

## Sections (from the client brief)

| # | Section | What's in it |
|---|---------|--------------|
| 01 | Hero | Swap card as hero, stripped to amount + two tokens + one button at rest. Typing an amount reveals dollar values, a short "checking pools" beat, then rate, route and the Kyber edge. Brand rails carry tokens in and out. |
| 02 | How Route works | Animated split-routing diagram that auto-plays Scan → Split → Check → Sign, plus the Route v2 vs Kyber / 0x / Nordstern proof card. |
| 03 | Onchain markets | Stocks lead (NVDA card with chart and Buy), category pills (Stocks, ETFs, Commodities, Majors, Launchpads), ticker grid, marquee. |
| 04 | Builders | Dark block: Partner API call, streaming quote line, quote+build, streaming quotes, zaps, partner fees, logo wall. |
| 05 | Coverage by chain | Robinhood Chain card + chain-by-product matrix (swap, limit, API, earn, screener). |
| 06 | Close | Big wordmark, tagline, Launch app, footer. Not in the brief. |

## Sources

Stats, case study numbers, API shape and builder fee cap (50 bps) are from docs.route.fun and route.fun/analytics (Oct 2026). Stock prices are samples from route.fun/yield. Streaming quotes and the non-Robinhood chains are flagged in the page as "confirm".
