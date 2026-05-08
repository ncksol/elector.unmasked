# Elector unmasked

A live-scoring fork of [elector.uk](https://elector.uk).

The original quiz is a 50-question UK political alignment tool. This fork keeps every question, every party stance value, and the full scoring algorithm intact — but adds two transparency features:

- **Live scoreboard.** Every party's match percentage is visible in a sticky panel beside the question and updates after every answer.
- **Hover-preview.** Hover or focus any Likert option and the scoreboard shows where each party would land *if you committed that answer*, with colour-coded delta chips. Move off to clear; click to commit.

The cubic amplifier from the original is preserved, but the results screen offers an "unamplified" toggle so the underlying linear correlation is also visible.

This is a static single-file app — no backend, no analytics, no data leaves your browser.

## Live site

https://ncksol.github.io/elector.unmasked/

## Source

Single self-contained `index.html`. Open it locally in any modern browser, or host it anywhere that serves static files.

## Credits

Questions, party stance codings, and scoring formula are taken verbatim from the original [elector.uk](https://elector.uk) by Ivan Katlianik. This fork is independent and not affiliated.
