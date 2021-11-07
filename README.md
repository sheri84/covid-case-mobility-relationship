# covid-case-mobility-relationship
Here I investigated the correlation between exponential coefficient of spread of disease, beta, and google mobility parameters. The main result is in "mongodb-pandas/main.ipynb" that the relationship is investigated for Melbourne and very high correlation is shown between mobility parameters and beta:
correlation of beta with transit_stations_percent_change_from_baseline :  0.61
correlation of beta with workplaces_percent_change_from_baseline :  0.22
correlation of beta with residential_percent_change_from_baseline :  -0.18

The same test is done in "pyspark/main.ipynb" for Australia and the UK. Sign of correlations are still as expected but values are much lower. This is because averaging over all areas in the country hides relationship. 



