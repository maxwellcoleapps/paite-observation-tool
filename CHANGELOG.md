# PAITE Observation Tool — Version History

Live app: https://maxwellcoleapps.github.io/paite-observation-tool/

Each entry lists what changed and when it went live. Times are US Eastern (UTC-4).

---

## v1.2 — July 2, 2026, 2:50 PM

- Growth suggestions in the post-observation report now include EXCL (Address Exclusionary Acts) and IDEN (Questions Based on Group Identity) when they were not observed.
- Removed the five-item cap on suggestions. Every unobserved practice is now listed.
- Reworded the report's caveat note: context-dependent codes may sit at zero when no relevant event occurred.

## v1.1 — July 2, 2026, 2:26 PM

- Added a code distribution pie chart to the observation summary screen, modeled on the PAITE data visualization template. Color-coded legend with counts and percentages.
- Added a downloadable post-observation report matching the PAITE report template: observation details, most-observed methods, pie chart, behavior frequency table, notes highlights, and growth suggestions. Downloads as an HTML file that prints cleanly to PDF.
- Added a project description and live link to the README (2:43 PM).

## v1.0 — July 2, 2026, 2:00 PM

- First public release on GitHub Pages.
- Full observation workflow: setup form, 2-minute interval timer, 16 PAITE behavior codes, interval notes, autosave, history, summary with frequency table and 10-minute pattern, CSV export, print view.
- Storage fallback added so the app works in restricted browsers instead of showing a blank page.
- All data stays in the observer's own browser. Nothing is sent to a server.
