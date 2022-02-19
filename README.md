
# appex-09 Starter Files

<!-- badges: start -->
<!-- badges: end -->




Do people in the US who quit smoking between 1972 and 1982 weight more in 1982 compared to those who did not quite smoking?

1. Using the `ggdag` package draw a DAG for the causal question
1. Determine the ideal "adjustment set(s)"
1. `install.packages("causaldata")`
1. Examine the variables included in the data by looking at the `nhefs_codebook`
1. Mark any variables in your DAG that **aren't** in this dataset as latent and examine the adjustment sets
1. `install.packages("broom")`
1. Fit a propensity score model using the confounders you identified that are in the NHEFS data
1. Create a mirrored histogram of your propensity scores
1. Update the theme of and colors of your plot
1. Knit commit & push to GitHub
