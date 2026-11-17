# apple-browning
A randomized experiment comparing lemon juice, bottled lemonade, and lemon soda in preventing apple browning.

##Files##
Jo_Kim_GU4724_Practicum.pdf: Final write-up, experimental design, results, and discussion.

apple_browning_Analysis.Rmd: R code for randomization, statistical analysis, hypothesis tests, and figures.

apple_browning_PAP.Rmd: Pre-analysis R code, the time stamped version is on: https://osf.io/py4d5/overview?view_only=86ea3fe5e2f14ea9ab7aedc2e710bcef

scores.csv: Experimental data for 100 apple slices.

code_0.jpg, code_1.jpg, code_2.jpg: Examples of the three browning-score categories.

noninterference.jpg: Photograph of the experimental setup.

##Replication:##
Place `apple_browning_Analysis.Rmd` and `scores.csv`
in the same directory.

Install the required R packages:

```r
install.packages(c(
  "ggplot2", "dplyr", "ri2", "randomizr",
  "estimatr", "broom", "rmarkdown"
))
```
