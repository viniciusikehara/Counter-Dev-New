# architecture

How the system is put together — layers, boundaries, and how data flows.

## The counter's score is kept in memory only (a JS variable), with no persistence (no local…

What: The counter's score is kept in memory only (a JS variable), with no persistence (no localStorage/backend) · Why: acceptance criteria explicitly require the score to reset to 0 on page refresh · Where: index.html inline script <!-- id: 6ca9e5c2-507f-4c3b-9fff-3db98ed10712-1 -->
