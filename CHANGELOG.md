# Changelog

## v1.0.0 (2026-11-06)

First release: the Chicago author-date citation format for SlideMage 0.13.0 or later.

- `SlideMage_citation_chicago.tex`: biblatex-chicago (`authordate`, the 17th edition's author-date system), adapted to SlideMage's slides (beamer's bibliography fonts and
  item icon, the footnote form of `\fullcite`).
- Tested with lualatex and biber on `@article`, `@book`, `@incollection`, `@report`, `@online` and a work with four
  authors, with `\parencite`, `\textcite`, `\cite` and `\fullcite` in a footnote.
