Multiverse Analysis in R
================

<div style="padding: 2em;">

<img src="https://github.com/masurp/specr/raw/master/man/figures/README-unnamed-chunk-2-1.png" width = 380 align="right" />

</div>

Welcome to the workshop on *Multiverse Analysis in R*. This page will be
used to distribute the slides, handouts, and other materials for this
course. All material is free to re-use under the
[CC-BY](https://github.com/masurp/workshop_bayes/blob/main/LICENSE.md)
license.

Empirical results depend on the conceptual and analytical choices made
by the researcher. For example, researchers need to decide how variables
should be operationalized and estimated, which variables to control for,
which observations to exclude, what to do with missing values, which
functional form to assume, which subgroups to analyse, what model to
choose and so on. When interpreting study outcomes, we seek genuine
insights into the underlying relationships under scrutiny. Achieving
this goal hinges on the premise that reported analyses accurately
represent the pool of valid analyses that could have been conducted – a
condition frequently unmet. One issue is that published results may
hinge upon arbitrary decisions made by researchers. Another concern is
the inclination of researchers to favor evidence that aligns with their
assumptions rather than presenting contrary evidence.

Multiverse-style methods (also known as specification curve analysis or
vibration of effects) have been proposed as a possible solution to this
dilemma. The idea is to estimate an effect across the entire set of
possible specifications to expose the impact of hidden degrees of
freedom and/or obtain robust, less biased estimates of the effect of
interest. However, this does not come with potential pitfalls: if the
investigated specifications are not truly arbitrary, multiverse-style
analyses can produce misleading results, potentially hiding meaningful
effects within a mass of poorly justified alternatives.

The workshop aims to equip participants with the knowledge to
meaningfully apply multiverse/specification curve analyses to their own
research. The 1-day workshop covers (1) a theoretical introduction to
the concept of researcher’s degrees of freedom and the problem of
undisclosed flexibility in data analyses, (2) an in-depth discussion of
how multiverse approaches may help to establish better practices and
more transparency in this regard, and (3) practical tutorial sessions
illustrating how to use the package `specr` to conduct
multiverse/specification curve analyses in R.

The workshop will be held by [Dr. Philipp K.
Masur](https://www.philippmasur.de) (Vrije Universiteit Amsterdam), who
is the developer of the R package `specr`. As we will run practical
analyses in R, prior programming experience in R and familiarity with
RStudio is an asset.

<br><br>

## Preparation

All materials and slides can be found on this webpage:
<https://masurp.github.io/workshop_specr/>.

For this 1-day workshop, I expect you…

1.  …to have R and RStudio installed. If you haven’t done so yet, have a
    look at this [getting
    started](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_basics_1_getting_started.md)
    tutorial, which walks you through the installation and helps you get
    some first hands-on experience using R. If possible, try to install
    the R package `specr`, which we will use to run multiverse analyses:

``` r
install.packages("specr")
```

2.  …to have some basic knowledge of R and particularly data wrangling
    skills (at best, some knowledge about the `tidyverse`). If this is
    still new to you, we have several videos and tutorials on our [R
    course material GitHub
    page](https://github.com/ccs-amsterdam/r-course-material) that can
    help you getting started. I would suggest to check out the tutorials
    on transforming, summarizing, visualizing and reshaping data in the
    “data wrangling with the tidyverse” category.

3.  …some basic knowledge of regression models (e.g., linear regression,
    logistic regression, multilevel linear regression).

**Note:** The workshop will NOT provide an introduction to R!

<br><br>

### Morning

| Time          | Topic                                                  |
|:--------------|:-------------------------------------------------------|
| 09:00 - 09:30 | Statistical Fortune-Telling                            |
| 09:30 - 10:00 | A Garden of Forking Paths                              |
| 10:00 - 11:00 | R: Exercise I: Basic Mechanisms of Multiverse Analysis |
| 11:00 - 12:00 | Into the Multiverse                                    |

### Afternoon

| Time          | Topic                                            |
|:--------------|:-------------------------------------------------|
| 13:00 - 13:45 | Arbitrary Decisions                              |
| 13:45 - 14:45 | R: Exercise II: Multiverse Analysis with `specr` |
| 14:45 - 15:30 | A Mass of Poorly Justified Alternatives          |
| 16:00 - 16:30 | R: Exercise III: Advanced Specifications         |

<br><br>
<hr>

This course is published under the following
[license](https://github.com/masurp/workshop_specr/blob/main/LICENSE).
