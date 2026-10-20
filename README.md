# Route landing: wireframe

Wireframe for the new [route.fun](https://www.route.fun) landing page. Single static file, no build step. Light mode, Route tokens, same style as [route-chat](https://github.com/todels/route-chat) and [route-earn](https://github.com/todels/route-earn).

**Local:** `python3 -m http.server 5204 -d .` then open http://localhost:5204

The button at the bottom right toggles the wireframe notes on and off. Animations are rough motion ideas, not final.

## Sections (from the client brief)

| # | Section | What's in it |
|---|---------|--------------|
| 01 | Hero | Swap card as hero, stripped to amount + two tokens + one button at rest. Typing an amount reveals dollar values, a short "checking pools" beat, then rate, route and the Kyber edge. Brand rails carry tokens in and out. |
| 02 | How Route works | Diagram loops Scan → Split → Check → Sign while on screen, with tokens flowing down each route. Trade size ($10 / $1,000 / $25,000) changes the split. Proof bars fill on scroll. |
| 03 | Onchain markets | Category pills switch the list, any row becomes the lead card, prices tick live, chart redraws per range with hover crosshair, Buy loads the token into the hero. |
| 04 | Builders | Feature cards drive the code panel: quote, live streaming log, zap legs, partner fee calculator wired into the code. Moving logo strip. |
| 05 | Coverage by chain | Chain card that follows whatever you click in the matrix, product filters on the matrix. |
| 06 | Close | Big wordmark, tagline, Launch app, footer. Not in the brief. |

## Sources

Stats, case study numbers, API shape and builder fee cap (50 bps) are from docs.route.fun and route.fun/analytics (Oct 2026). Stock prices are samples from route.fun/yield. Streaming quotes and the non-Robinhood chains are flagged in the page as "confirm".
