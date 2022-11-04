<!-- README.md is generated from README.Rmd. Please edit that file -->

# SpipollV2

<!-- badges: start -->
<!-- badges: end -->

Research Compendium of the project **{{ PLEASE ADD A FEW WORDS }}**

### How to cite

Please cite this compendium as:

> **{{ PLEASE ADD A CITATION }}**

### Content

This repository is structured as follow:

-   [`data/`](https://github.com/charles-thevenin/SpipollV2/tree/master/data):
    contains all raw data required to perform analyses

-   [`analyses/`](https://github.com/charles-thevenin/SpipollV2/tree/master/analyses/):
    contains R scripts to run each step of the workflow

-   [`outputs/`](https://github.com/charles-thevenin/SpipollV2/tree/master/outputs):
    contains all the results created during the workflow

-   [`figures/`](https://github.com/charles-thevenin/SpipollV2/tree/master/figures):
    contains all the figures created during the workflow

-   [`R/`](https://github.com/charles-thevenin/SpipollV2/tree/master/R):
    contains R functions developed especially for this project

-   [`man/`](https://github.com/charles-thevenin/SpipollV2/tree/master/man):
    contains help files of R functions

-   [`DESCRIPTION`](https://github.com/charles-thevenin/SpipollV2/tree/master/DESCRIPTION):
    contains project metadata (author, date, dependencies, etc.)

-   [`make.R`](https://github.com/charles-thevenin/SpipollV2/tree/master/make.R):
    main R script to run the entire project by calling each R script
    stored in the `analyses/` folder

### Usage

Clone the repository, open R/RStudio and run:

    source("make.R")

### Notes

-   All required packages, listed in the `DESCRIPTION` file, will be
    installed (if necessary)
-   All required packages and R functions will be loaded
-   Some analyses listed in the `make.R` might take time
