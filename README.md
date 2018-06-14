rr-automation
=============

This lesson teaches some tips and tricks that will make life easier with `RMarkdown` if one is using it in the context of a typical research project, which will likely involve multiple sources of raw data that are then combined to create multiple intermediate datasets which then get combined to generate figures and tables.

## Before the lesson starts

- Make sure that participants have the following packages installed:
  - `knitr`
  - `tidyverse`
  - `testthat`
  - `rmarkdown` and `knitr` (in `RStudio` pushing the knit HTML button the first time will prompt to have these packages installed)

- Distribute a Zip file that only contains the content of the
  `example-manuscript` folder from this repository.

- Explain what the handout file contains

## Submodules

[Automation] (01-automation-instructor-notes.md)
This lesson outlines the manuscript and begins the process. Beginning with the data, the lesson explores the '''manuscript-inline.Rmd'''. 

[Writing Functions in R] (02-functions-instructor-notes.md)
Basic lesson in writing functions using R

[Functions for Data] (03-functions-for-data-notes.md)
Writing functions to automate data gathering and sharing them. 

[Function for Figures] (04-functions-for-figures-notes.md)
Writing functions to provide figures for papers. 
## People and credits

This lesson was first created at the [1. Reproducible Science Curriculum Hackathon]. The corresponding author is **François Michonneau** ([@fmichonneau]). See the commit log for other contributors.

Please post feedback and issues with the lesson on the repository's issue tracker. For instructor questions about teaching this lesson, you can also contact the corresponding author directly.

[@fmichonneau]: https://github.com/fmichonneau
[1. Reproducible Science Curriculum Hackathon]: https://github.com/Reproducible-Science-Curriculum/Reproducible-Science-Hackathon-Dec-08-2014
