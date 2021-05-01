
# Tutorials for intro stats 2021

The package includes tutorials for intro stats 2021. The tutorials can
be launched using this package and run on your local machine. These
tutorials are built with
[{learnr}](https://rstudio.github.io/learnr/publishing.html).

## Installation

To use the tutorials, you should first install {learnr} as well as this
package of tutorials. To install these, run the following commands:

``` r
# install.packages("remotes")
install.packages("learnr")
remotes::install_github("maia-sh/introstats2021exercises")
```

## Run a tutorial

``` r
learnr::run_tutorial("exercise_1_intro", package = "introstats2021exercises")
```
