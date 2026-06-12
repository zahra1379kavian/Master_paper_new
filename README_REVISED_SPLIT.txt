Revised Frontiers LaTeX split package
====================================

Files to upload/compile:
- main.tex: revised main manuscript. It does NOT input the supplement at the end.
- supplementary_material.tex: revised supplementary material as a separate file.
- references.bib, Frontiers-Harvard.bst, FrontiersinHarvard.cls, frontiers_suppmat.cls: bibliography/style/class files.
- main_figures/ and supplementary_figures/: original figure assets used by the revised files.

Compilation tested in this environment with:
  pdflatex main.tex
  bibtex8 main
  pdflatex main.tex
  pdflatex main.tex

and:
  pdflatex supplementary_material.tex
  bibtex8 supplementary_material
  pdflatex supplementary_material.tex
  pdflatex supplementary_material.tex

Author-side fields that still need final completion:
- co-author names, affiliations, and corresponding author email;
- Ethics Statement, Conflict of Interest Statement, Author Contributions, Funding,
  Acknowledgments, Data Availability Statement;
- any required disclosure about generative-AI assistance, according to Frontiers policy;
- final check of exact article type, journal selection, and manuscript metadata in the Frontiers portal.
