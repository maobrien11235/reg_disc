# reg_disc
Exploration of discontinuity regression for causal analysis.

## Hypothesis
This project is meant to explore causal effect modeling. I explore this topic by testing the hypothesis that banks with higher regulatory scrutiny need to hold more regulatory capital. I test this hypothesis by using Regression Discontinuity Design (RDD) on banks that are just over the $10BB in consolidated assets mark. The $10BB threshold requires banks to submit their financials to Federal Reserve stress tests, whereby the bank must forecast its losses to ensure it will remain well-capitalized under economically stressed scenarios. 

## DataSet Design
I create a dataset of banks around $10BB in consolidated assets. I chose to include banks between $8BB and $12BB, which resulted in a sample of 24 banks. The consolidated asset numbers for each bank is pulled from the [March 2019 report](https://www.federalreserve.gov/releases/lbr/current/) on bank size. I used publicly-reported Common Equity Tier 1 ratios as a proxy for bank capitalization. I retrieved this data by manually searching through each of the 24 banks in the asset window above. 
