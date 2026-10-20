# Route landing: wireframe

Wireframe for the new [route.fun](https://www.route.fun) landing page. Single static file, no build step. Light mode, Route tokens, same style as [route-chat](https://github.com/todels/route-chat) and [route-earn](https://github.com/todels/route-earn).

**Local:** `python3 -m http.server 5204 -d .` then open http://localhost:5204

The button at the bottom right toggles the wireframe notes on and off. Animations are rough motion ideas, not final.

## Sections (from the client brief)

| # | Section | What's in it |
|---|---------|--------------|
| 01 | Hero | Swap card as hero, stripped to amount + two tokens + one button at rest. Typing an amount reveals dollar values, a short "checking pools" beat, then rate, route and the Kyber edge. No background graphic. |
| 02 | How Route works | Four steps beside an isometric scene (liquidity-pool platform between your token and the output). Steps auto-advance or click: Scan sweeps a beam over the pools, Split arcs the trade into the best three, Check ticks them and boxes the route as a simulation, Sign merges it all into the output. Motion idea, final illustration to be designed. |
| 03 | Onchain markets | No charts. Moving wall of tradeable stocks, ETFs and gold, crypto. Head-to-head: the same order through Route vs Nordstern, 0x and Kyber, rows race into place. Click any chip to compare that asset. |
| 04 | Builders | Feature cards drive the code panel: quote, live streaming log, zap legs, partner fee calculator wired into the code. Moving logo strip. |
| 05 | Coverage by chain | Chain card that follows whatever you click in the matrix, product filters on the matrix. |
| 06 | Close | Big wordmark, tagline, Launch app, footer. Not in the brief. |

## Sources

Stats, case study numbers, API shape and builder fee cap (50 bps) are from docs.route.fun and route.fun/analytics (Oct 2026). Stock prices are samples from route.fun/yield. Streaming quotes and the non-Robinhood chains are flagged in the page as "confirm".
