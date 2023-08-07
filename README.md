## Background

This manuscript provides context and details about the smdi R package
that was developed as a result of the findings of a comprehensive
Sentinel Innovation Center project on
`principled approaches on partially observed confounder data` in
electronic health records.

More information about the package can be found under:
<https://janickweberpals.gitlab-pages.partners.org/smdi>

## Structure

-   .Rprofile - defines paths and activates `renv`, options for Posit R
    package manager
-   tables - main and supplementary tables (R objects and .docx format)
-   figures - main and supplementary figures (R objects and .docx
    format)
-   renv/renv.lock - `renv` directories to manage R dependencies and
    versions used in this simulation

## Dependencies

R package dependencies are managed through the `renv` package. All
packages and their versions can be viewed in the lockfile `renv.lock`.
All required packages and the appropriate versions can be installed by
running the following command:

    renv::restore()

## Directory overview

    fs::dir_tree(recurse = 1)

    ## .
    ## ├── README.Rmd
    ## ├── README.md
    ## ├── figures
    ## │   ├── Figure_1_workflow.jpg
    ## │   ├── Figure_2_visuals.jpg
    ## │   ├── Figure_3_results.jpg
    ## │   └── manual_figures.pptx
    ## ├── manuscript
    ## │   ├── cover_letter.docx
    ## │   ├── custom-reference-doc.docx
    ## │   ├── docx-landscape.lua
    ## │   ├── jamia.csl
    ## │   ├── manuscript.docx
    ## │   ├── manuscript.qmd
    ## │   └── references.bib
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
