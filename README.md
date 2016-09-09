#Scripts and results from a new test for complex selection

## Directory 1: Chickens

This directory houses scripts and results for analyzing complex selection in brown and white laying chickens. Data is not included due to GitHub size restrictions.

**PDF and PNG Documents** Figures that were generated as part of the analysis

**Frequency_change_rrBlup.Rmd** Code to run the analysis using R-markdown

**Frequency_change_rrBlup.html** HTML document with code and results.

## Directory 2: Maize

**GWAS_Effects** R-markdown code and html document for estimating SNP effects using GWAS

**Frequency_change_GWAS** R-markdown code and html document for analyzing maize data using GWAS effects estimates

**Frequency_change_rrBlup** R-markdown code and html document for analyzing maize data using rrBlup effects estimates

**Sub-directory 2.1** This directory houses all figures from the above scripts. Figures ending with "_rrblup" were analyzed using rrblup estimates. The other figures were analyzed using GWAS estimates.

## Directory 3: Simulations

**analyzeSims_something_something_something** R-markdown code and html document for analyzing simulated data. The first **something** indicates the total number of QTL simulated: 10, 100, or 200. The second **something** is the abbreviation "rnd", and is not always present. Files appended with "rnd" were simulations where no selection occurred. The third **something** is the text "GWAS" or "rrblup". These indicate whether effects estimates came from GWAS or rrblup. Figures are housed within the html files.

