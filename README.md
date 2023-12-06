# smdi: An R package to perform structural missing data investigations on partially observed confounders in real-world evidence studies

[![DOI](https://zenodo.org/badge/675783358.svg)](https://zenodo.org/doi/10.5281/zenodo.10267623)

## Background

This manuscript provides context and details about the smdi R package
that was developed as a result of the findings of a comprehensive
Sentinel Innovation Center project on
`principled approaches on partially observed confounder data` in
electronic health records.

More information about the package can be found under:
<https://janickweberpals.gitlab-pages.partners.org/smdi>

## Structure

-   manuscript - manuscript, bibliography, cover letter and meta files
    to render to .docx format
-   tables - main and supplementary tables (R objects and .docx format)
-   figures - main and supplementary figures (R objects and .docx
    format)
-   renv/renv.lock - `renv` directories to manage R dependencies and
    versions used in this simulation
-   .Rprofile - defines paths and activates `renv`, options for Posit R
    package manager

## Dependencies

R package dependencies are managed through the `renv` package. All
packages and their versions can be viewed in the lockfile `renv.lock`.
All required packages and the appropriate versions can be installed by
running the following command:

    renv::restore()

## Directory overview

    ## .
    ## ├── README.Rmd
    ## ├── README.md
    ## ├── figures
    ## │   ├── Figure_1_workflow.png
    ## │   ├── Figure_2_visuals.png
    ## │   ├── Figure_3_results.png
    ## │   └── manual_figures.pptx
    ## ├── manuscript
    ## │   ├── Responses JAMIO-2023-0165_R1.docx
    ## │   ├── custom-reference-doc.docx
    ## │   ├── docx-landscape.lua
    ## │   ├── jamia.csl
    ## │   ├── manuscript.docx
    ## │   ├── manuscript.qmd
    ## │   ├── manuscript_track_changes.docx
    ## │   ├── references.bib
    ## │   ├── supplement.pdf
    ## │   └── supplement.qmd
    ## ├── renv
    ## │   ├── activate.R
    ## │   ├── library
    ## │   ├── sandbox
    ## │   ├── settings.dcf
    ## │   ├── settings.json
    ## │   └── staging
    ## ├── renv.lock
    ## ├── smdi-manuscript.Rproj
    ## └── tables
    ##     └── tables_manual.xlsx
