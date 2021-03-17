# README.md

Welcome to the MP429 repository! This repository contains materials to support the following workshops:

- Statistics I: Statistics in Pharmacy
- Statistics II: Data visualisation and what can go wrong

presented as part of MP429: New Medicines, Better Medicines, Better Use of Medicines, at the University of Strathclyde.

The material you are viewing relates to the 2020-21 presentation of the course, and was prepared by

- [Dr Leighton Pritchard](https://github.com/widdowquinn)
- [Dr Nik Rattray](https://www.strath.ac.uk/staff/rattraynicholasdr/)
- [Dr Zahra Rattray](https://www.strath.ac.uk/staff/rattrayzahradr/)

## How Do I Use This Repository?

We use the code in this repository to generate 

1. standalone HTML files that can be used with MyPlace. 
2. [`Shiny`]() webapps that can be run by students on their own machines, or at [`rstudio.org`]()

The code is written in [`R`]() using [`R Markdown`](), and to use or generate all of the materials, we recommend that you install and use [`RStudio`]().

In addition, the materials require the following `R` packages:

- [`DT]() for interactive data tables in standalone HTML pages
- [`plotly`]() for interactive graphs in standalone HTML pages

and these can be installed from `RStudio` by opening the `install.R` script and clicking on the `Run` button, or from the command-line using:

```bash
Rscript install.R
```

## Notebook HTML

The current versions of the notebook HTML pages are linked below, for convenience

- [1. Why Do We Do Statistics?](notebooks/01-statistics.html)
  - [1a. Exploring a Statistical Distribution **INTERACTIVE SESSION**](https://mp429.shinyapps.io/01a-sampling/)
  - [1b. Exploring a Statistical Relationship **INTERACTIVE SESSION**](https://mp429.shinyapps.io/01b-linear/)  
- [2. What is a Dataset?](notebooks/02-dataset.html)
- [3. An Introduction to Data Visualisation](notebooks/03-visualisation.html)
  - [3a. Better Tools Than Bar Charts **INTERACTIVE SESSION**](https://mp429.shinyapps.io/03a-barchart/)
- [4. Where Do Statistical Distributions Come From?](notebooks/04-origins.html)
  - [4a. Where Does the Normal Distribution Come From?](https://mp429.shinyapps.io/04a-generate-normal/)
- [5. Hypothesis Testing](notebooks/05-origins.html)