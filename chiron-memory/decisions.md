# decision

A choice made and the reasoning behind it — the path taken over the alternatives.

## The counter page is built as a single self-contained index.html with inline CSS/JS, no fr…

What: The counter page is built as a single self-contained index.html with inline CSS/JS, no framework or build step · Why: requirements are one page with one interaction, so a framework/build pipeline would add setup cost with zero benefit; a static file can be opened directly or served by any static server · Where: index.html (repo root) · Learned: this founds the project's architecture for future features. <!-- id: 6ca9e5c2-507f-4c3b-9fff-3db98ed10712-0 -->

## The counter page's UI must use a red button with a red accent on the score display, with…

What: The counter page's UI must use a red button with a red accent on the score display, with a centered layout · Why: these are explicit acceptance criteria from the work order (visible score starting at 0, visible red button), not just an aesthetic choice · Where: index.html inline CSS · Learned: don't drop the color/layout requirements when reasoning about the page — 'red counter' isn't just a name, red is a spec requirement. <!-- id: 6ca9e5c2-507f-4c3b-9fff-3db98ed10712-3 -->
