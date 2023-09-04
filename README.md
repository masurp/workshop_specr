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

For this 2-day workshop, I expect you…

1.  to have R and RStudio installed. If you haven’t done so yet, have a
    look at this [getting
    started](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_basics_1_getting_started.md)
    tutorial, which walks you through the installation and helps you get
    some first hands-on experience using R. You do not need to install
    the packages that we will use in the workship yet. We will install
    those together in the workshop.

2.  to have some basic knowledge of R and particularly data wrangling
    skills (at best, some knowledge about the `tidyverse`). If this is
    still new to you, we have several videos and tutorials on our [R
    course material GitHub
    page](https://github.com/ccs-amsterdam/r-course-material) that can
    help you getting started. I would suggest to check out the tutorials
    on transforming, summarizing, visualizing and reshaping data in the
    “data wrangling with the tidyverse” category.

3.  a good understanding of descriptive statistics (distributions,
    parameters of central tendency) and frequentist inference (standard
    error, p-value, confidence intervals).

4.  some basic knowledge of regression models (e.g., linear regression,
    logistic regression, multilevel linear regression). In the practical
    part of the workshop, we will fit such models in R.

**Note:** The workshop will NOT provide an introduction to R!

<br><br>

<br><br>
<hr>

This course is published under the following
[license](https://github.com/masurp/workshop_specr/blob/main/LICENSE).
