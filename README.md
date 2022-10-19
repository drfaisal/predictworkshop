
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Development and Validation of Clinical Prediction Models (CPM) in R Workshop

### Slides

-   [00
    Intro](https://causal-inference-r-workshop.netlify.app/00-intro.html)
-   [01 Whole
    Game](https://causal-inference-r-workshop.netlify.app/01-causal_modeling_whole_game.html)
-   [02 Causal
    Diagrams](https://causal-inference-r-workshop.netlify.app/02-dags.html)
-   [03 Introduction to Propensity
    Scores](https://causal-inference-r-workshop.netlify.app/03-pscores.html)
-   [04 Using Propensity
    Scores](https://causal-inference-r-workshop.netlify.app/04-using-pscores.html)
-   [05 Checking Propensity
    Scores](https://causal-inference-r-workshop.netlify.app/05-pscore-diagnostics.html)
-   [06 Fitting the outcome
    model](https://causal-inference-r-workshop.netlify.app/06-outcome-model.html)
-   [07
    G-Computation](https://causal-inference-r-workshop.netlify.app/07-g-computation.html)
-   [08 Tipping Point Sensitivity
    Analyses](https://causal-inference-r-workshop.netlify.app/08-tipr.html)

### Installing materials locally

We will be using RStudio Cloud for the workshop, but if you would like
to install the required packages and course materials, we have an R
package called
{[predictworkshop](https://github.com/drfaisal/predictworkshop)} to
help you do that! You can install
{[predictworkshop](https://github.com/drfaisal/predictworkshop)}
from GitHub with:

``` r
install.packages("remotes")
remotes::install_github("drfaisal/predictworkshop")
```

Once you’ve installed the package, install the workshop with

``` r
predictworkshop::install_workshop()
```

By default, this package downloads the materials to a conspicuous place
like your Desktop. You can also tell `install_workshop()` exactly where
to put the materials:

``` r
predictworkshop::install_workshop("a/path/on/your/computer")
```
