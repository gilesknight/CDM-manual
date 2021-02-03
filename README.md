# CDM-manual

<!-- badges: start -->

![](https://img.shields.io/badge/book--coverage-minimal-red)[![GitHub issues](https://img.shields.io/github/issues/gilesnknight/CDM-manual)![GitHub license](https://img.shields.io/github/license/gilesnknight/CDM-manual)](https://github.com/gilesnknight/CDM-manual/issues)

<!-- badges: end -->

The goal of CDM-manual is to provide an easily editable "living manual" that describes the set-up and results of the Coorong Dynamics Model (CDM).

## Contributing

This manual was built using the R [bookdown](https://github.com/rstudio/bookdown) package - an extension of the [rmarkdown](https://github.com/rstudio/rmarkdown) package designed for writing long-form documents and generating outputs in multiple formats.

Below are basic instructions to help you get started editing the manual. For a detailed contribution guide, please read the [Contributing chapter](https://gilesnknight.github.io/CDM-manual/contributing.html) of the manual.

#### 1. Prerequisites

For the best experience, we recommend editing the manual using the [RStudio IDE](https://rstudio.com). Once installed, use the console to download the bookdown package:

```{r}
install.packages("bookdown")
```

#### 2. Clone the repository

Clone CDM-manual using [GitHub Desktop](https://desktop.github.com) or from your terminal:

```{bash}
git clone https://github.com/gilesnknight/CDM-manual.git
```

#### 3. Edit a chapter

Open the R project file `CDM-manual.Rpoj` and navigate to the `.Rmd` file that corresponds the desired chapter you wish to edit.
