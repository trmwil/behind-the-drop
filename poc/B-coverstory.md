# B — COVER STORY

**Direction:** a premium games-culture magazine that moves — the Apex slide's editorial layout grown into a full talk language: giant Anton mastheads overlapping key art, `No. 01` folios, `// EYEBROW` labels, hairline rules, an orange pull-quote rail, and a magenta↔orange accent shift between beats (orange cover → magenta feature → orange roster → magenta drop).

**Signature transition — "text as window":** the outgoing masthead word (`DROP`, `LAUNCH`, `ROSTER`) is mirrored as an SVG `clipPath` text placed exactly over the DOM word (canvas font metrics), filled with the next beat's cover art; the page goes to black behind the letters, the word scales up around an ink pixel (so it always opens to a full frame) while the next page's scrims settle inside the window, then the plate fades and the new layout's hairline draws across. ~1.3 s, transform/opacity/clip only. Every headline uses the masked wordmark rise; beat 1 cold-opens with a diagonal clip-path curtain.

**Roster reuse (beat 3):** the 25 portraits + ensemble first land as a photographer's proof sheet inside a film strip (frame numbers `FR 01–26`, roll labels, grease-pencil picks on four frames), then the wash lifts and the same tiles become the two-row seamless marquee — the sheet *is* the marquee before it moves.

**Carries into a 20-slide deck:** the folio/rule/eyebrow chrome, the cover→feature→spread page types, the window transition keyed off any Anton word, the film-strip strip as a reusable "team" module, stat cards, GHC stamp; `COVERS` descriptor drives both page backgrounds and window fills from one source of truth.

**Limits / next:** transition verified only by frozen frames in headless Chrome (`#beat=1&debug=go:0.8`), not at runtime fps — the giant clipPath text in the last ~0.2 s should be profiled on the projector laptop; beat 4 loops the trailer from 20 s (the Steam cut's first 19 s are letterboxed with a legal card) and uses Steam screenshot `ss_04` as poster; pull-quote and body copy are placeholders; the `legends_group` ensemble stands in for the 26th frame (there are 25 individual portraits).
