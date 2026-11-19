# Changelog

## 2026-11-19 — Standalone template

- Extracted a standalone theme repository without the course-notes Git history or unrelated files.
- Retained the supplied Dongguan university logo and the burgundy/red/orange visual design; removed unused legacy color aliases.
- Replaced outdated FYP/2022 metadata and Hong Kong campus placeholders with editable CityUHK (Dongguan) bilingual examples.
- Added 16:9 examples covering headings, sections, lists, blocks, formulas and tables; pinned example CJK fonts to portable Fandol fonts.
- Removed local workspace files, VS Code user configuration scripts, machine-specific build entry points, old logos and unused course figures from the published file set.
- Rewrote README for portable XeLaTeX use; added source/status notice and ignored generated files.
- Validation results are recorded below after compilation and visual review.

### Validation

- Compiled with TeX Live 2026, XeLaTeX and latexmk; all 10 pages generated successfully with SyncTeX.
- Checked the final LaTeX log for overfull boxes and missing characters; none reported.
- Rendered all 10 pages with macOS PDFKit and reviewed Chinese/English text, school logo, title panel, section dividers, footer page counts, blocks, equations and tables; no clipping or overlapping text found.
- The bundled Poppler renderer lacked Adobe-GB1 mapping data, so its incomplete Chinese rendering was not used for the published previews; PDFKit confirmed Chinese text rendered correctly.
- Published source contains no local runtime paths or course-specific dependencies. Preview PDF and title image correspond to the included source.
