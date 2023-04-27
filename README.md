# TCI
Rank your gene list by combining layers of evidence in atherosclerosis. This tool allows you to aggregate pre-curated biological data and identify the most credible targets in your list.

# Basic algorithm
Our Basic algorithm has the purpose of scoring each biological layer with user-defined weights.  Internally, the algorithm uses data transformation functions specific to each data type: the raw data is transformed into the same interval of values [0-1] and later aggregated to score every gene independently.

R script funtions:  ext_functions_basic.R

# Biological layers of gene-disease association
We have downloaded datasets of relevance for atherosclerosis, curated the data and assigned biological layers.

The pre-computed scores data are available in this R object: transformed_datasets.RData

# Web-app tool
We hope you would find this tool useful for reducing long lists of genes, taking promising candidates to your validation assays or complementing the package of information around your favourite targets!

We wrote this app using shiny R with argonDash.
The ui code is: app.R
