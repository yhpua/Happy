
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Harrell’s added predictive performance yardstick (HAPPY)[^1]

## Background

This [webpage](https://yhpua.github.io/Happy/) documents the
functionality of the `Happy` `R` function. `Happy` computes several
statistical indexes (“yardsticks”) to quantify the added predictive
performance of “new” predictors over “old” predictors in binary and
ordinal outcome models. This `R` function is inspired by Prof Harrell’s
thoughtful and thought-provoking blog article, [Statistically Efficient
Ways to Quantify Added Predictive Value of New
Measurements](https://www.fharrell.com/post/addvalue/), and his more
recent thinking about the [modified adjusted Maddala-Cox-Snell $R^2$
values](https://hbiostat.org/bib/r2.html). `Happy` relies heavily on the
functions from the [`rms` R package](https://github.com/harrelfe/rms).

[^1]: I don’t mean to be flippant here. To judge from the responses on
    [Datamethods](https://discourse.datamethods.org/t/statistically-efficient-ways-to-quantify-added-predictive-value-of-new-measurements/2013),
    powerful likelihood ratio (LR)-based yardsticks like Adequacy Index
    (AI) and Relative Explained Variation (REV) have made many
    biomedical researchers very happy.
