# GeoAgent — project page

Static project page for **GeoAgent: Evaluating VLM Geolocalization Through Embodied
Navigation** (Findings of EMNLP 2026).

Arka Mukherjee, Soham Roy, Kartikeya Trivedi, Shreya Ghosh · CC BY 4.0

- Live: https://kartikeya-trivedi.github.io/geoagent/
- Code & environment: https://anonymous.4open.science/r/geoagent-1162
- Interactive companion: https://research.kartikeya.me/geoagent

## Layout

Single self-contained `index.html` — no build step, no dependencies. Served by GitHub
Pages straight from `main`. Figures in `img/` are extracted from the paper PDF and
reproduced under CC BY 4.0.

Styled as an academic document: white ground, single measured serif column with figures
and tables breaking out wider, numbered sections, `booktabs` tables (horizontal rules
only), numbered figures with captions below, and LaTeX-style numbered equations.

## Notes

- Table 3 is generated at runtime from one data object, and the **bold (best) /
  underline (second-best)** marks are computed from the values rather than hand-authored
  — they cannot drift from the data. All 60 are verified.
- Wide figures and tables scroll inside their own containers, with a swipe hint that
  appears only when content genuinely overflows. The page body never scrolls
  horizontally (verified at 375 and 1280).
- The source paper has a couple of internal inconsistencies — notably the sign
  convention in its Figure 4 versus that figure's caption. The page leans on the
  mean-distance column, where every reported source agrees, and says so in the caption.
