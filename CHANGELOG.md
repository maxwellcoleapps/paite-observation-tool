# PAITE Observation Tool — Version History

Live app: https://maxwellcoleapps.github.io/paite-observation-tool/

Each entry lists what changed and when it went live. Times are US Eastern (UTC-4).

---

## v1.4 — July 4, 2026, 1:36 PM

- Added a data visualization generator to the summary. Pick a chart type and view it live: donut, pie, categorical pie (grouped into the 5 PAITE categories), horizontal bar, vertical bar, longitudinal bar, table, stacked bar by time, and stacked bar percent by time.
- Categorical pie groups the 16 codes into Science of Learning, Social Psychological, Classroom Climate, UDL & CRT, and Other, matching the spreadsheet template.
- The longitudinal chart compares codes across your saved observation sessions, pulled automatically from history (most recent six).
- Stacked-by-time charts use the 10-minute intervals. The percent version normalizes each interval to 100%.
- Report contents now lets you include any of these charts and graphs in the downloaded and emailed report, alongside the frequency table, 10-minute pattern, notes, context, and suggestions.

## v1.3 — July 4, 2026, 12:50 PM

- Setup form now uses a single required "Instructor Name or ID" field. The separate instructor name field was removed.
- Added an optional instructor email field.
- Added a pre-observation notes field for the instructor's teaching goals for the session.
- Class structure and class context are now optional at setup and editable at any point during the observation through a new "Class details & context" panel.
- Relabeled "Number of students" to "Number of students present."
- Growth suggestions in the report are now capped at 3 top practices to consider, and always exclude EXCL and IDEN. Those two codes still appear in the behavior frequency table. (Reverses the July 2 change that added them to suggestions and removed the cap.)
- Added report content checkboxes so the observer chooses which graphs and tables go in the downloaded report: code distribution chart, behavior frequency, 10-minute pattern, notes, class context, and suggestions.
- Added the 10-minute pattern table to the downloadable report.
- Added an "Email report" button that downloads the report and opens the observer's mail app addressed to the instructor, ready to attach and send.
- Added a "Clear all data" button on the setup and history screens that wipes the active draft and all saved observations from the browser.

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
