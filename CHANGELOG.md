# Changelog

All notable changes to the Sunny Launch site are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [0.1.0.0] - 2026-08-11

### Changed

- `/willa/` is now a showcase page. It says what Project Willa is, who it's for, and what it helps with, then sends you to willa.family to actually get it. The old page told the whole story on sunnylaunch.com; the product now has its own home, so this page introduces it and gets out of the way.
- The Willa nav and footer link out to willa.family instead of pointing back at themselves. On narrow screens the nav button shortens to "Willa.Family" so it fits the row.
- The nav on `/willa/` matches `/` and `/consulting/` again. It no longer swaps the Sunny Launch mark for the Willa mark as you scroll.

### Removed

- The how-it-works steps, the "rebuilding the village" section and its citations, the testimonial, the house rules, and the eleven-question FAQ. That material belongs with the product, not on the company site.
- The "Request an invite" mailto call to action. Willa.family handles signups now.
- The scroll listener that drove the nav mark cross-fade. The page ships with no JavaScript.

[0.1.0.0]: https://github.com/workwith-cmd/sunny-launch/releases/tag/v0.1.0.0
