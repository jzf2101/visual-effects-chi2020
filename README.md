# Replication materials for "How visualizing inferential uncertainty can mislead readers about treatment effects in scientific results"

This is code to reproduce the results and figures in "How visualizing inferential uncertainty can mislead readers about treatment effects in scientific results", by Jake M. Hofman, Daniel G. Goldstein, and Jessica Hullman, published in CHI 2020.

## Requirements

R, with the following packages: tidyverse, gridExtra, scales, broom, lsr, knitr, and lsmeans.

## Running the code

To reproduce results, simply run the Makefile by typing `make` on the command line, or open and run the `analysis.Rmd` file.

## Files

  * `analysis.Rmd`: Main analysis code in Rmarkdown format
  * `analysis.html`: Rendered output from running `analysis.Rmd` containing all results and figures in the paper
  * `data/experiment_1_clean.Rdata`: Clean data frames for first experiment
  * `data/experiment_2_clean.Rdata`: Clean data frames for second experiment
  * `figures/`: Directory containing rendered pdf figures used in the paper