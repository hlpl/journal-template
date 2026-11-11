# HLPL Journal Template (LaTeX)

Official template for the **Human Life Programming Language** journal.

> An overlay journal for the Physics of Meaning

- Journal site: https://journal.hlpl.net/
- Zenodo community: https://zenodo.org/communities/hlpl
- Template v1.0 (version of record): https://doi.org/10.5281/zenodo.24136657
- Publisher: Ahmida Bendjoudi — University Frères Mentouri Constantine 1

## Files

| File | What it is |
| --- | --- |
| `hlpl-template.tex` | Main template — copy this to start a new article |
| `hlpl.sty` | HLPL style — layout, title block, headings, tables, references |
| `hlpl-logo.png` | Journal logo (top-right of title block) |

## How authors use it

1. Download this repo (or the Zenodo v1.0 files)
2. Copy `hlpl-template.tex` → `my-article.tex`
3. Replace title, authors, abstract, sections — keep `\\hlplmaketitle`
4. Compile with pdfLaTeX / XeLaTeX (compile twice for references)
5. Submit the PDF to Zenodo + add it to the HLPL community

## Versioning rule

- **Zenodo is the version of record.** Every public release here must match a Zenodo version.
- Do not publish a new version on GitHub without creating the matching Zenodo release.
- v1.0 = the files published at https://doi.org/10.5281/zenodo.24136657

## How to submit a paper

There is no submission system on journal.hlpl.net.
Account and submission system is served with Zenodo:

1. Upload your PDF to https://zenodo.org/uploads/new
2. Add it to the HLPL community
3. Send your Zenodo DOI / link to the editor
