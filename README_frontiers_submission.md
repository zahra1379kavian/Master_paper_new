# Frontiers submission package

Prepared for the Research Topic **Brain imaging and stimulation for motor control and movement disorders** in **Frontiers in Human Neuroscience - Brain Imaging and Stimulation**.

## Main files

- `main.tex`: Frontiers Harvard manuscript file.
- `supplementary_material.tex`: separate supplementary material file, using the Frontiers supplementary class.
- `references.bib`: bibliography file.
- `main.pdf` and `supplementary_material.pdf`: compiled PDFs, if compilation succeeded.

## Items the author must complete before submission

1. Replace `Second Author` and `Third Author` with the real co-author names.
2. Add the exact affiliation details required by Frontiers: laboratory/institute/department, organization, city, province/state abbreviation, and country.
3. Add the corresponding author email in `\def\corrEmail{...}`.
4. Confirm or replace the Conflict of Interest statement.
5. Complete the Author Contributions statement using author initials.
6. Add funding sources and grant numbers, or state that no specific funding was received.
7. Complete the Data Availability Statement with repository/link or an appropriate access restriction.
8. Add acknowledgments if applicable, including any required AI-use disclosure.
9. Upload figures individually during Frontiers submission; the PDFs are included here for compilation, but Frontiers may request high-resolution EPS/JPEG/TIFF files after acceptance.
10. `Figure4.pdf` was present in the original ZIP but was not referenced in `main.tex`; it is copied here so it is not lost, but you should decide whether it should be used, renamed, or removed.

## Compile locally

Use pdfLaTeX and BibTeX:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
pdflatex supplementary_material.tex
pdflatex supplementary_material.tex
```

If `bibtex` is unavailable on your system but `bibtex.original` exists, run `bibtex.original main` instead of `bibtex main`.
