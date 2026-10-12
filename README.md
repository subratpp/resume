# resume

LaTeX CVs

- `cv_academic.tex`: academic CV (postdoc / faculty). Publications come from `references.bib`.
  Build: `pdflatex cv_academic && biber cv_academic && pdflatex cv_academic && pdflatex cv_academic`
- `cv_industry.tex`: 2-page industry resume (RL research / engineering roles). No bibliography.
  Build: `pdflatex cv_industry`
