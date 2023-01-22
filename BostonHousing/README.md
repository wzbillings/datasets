# Boston Housing Data

This data set contains 506 records of 14 fields about housing prices in
the Boston metro area.

## Source
The data are sourced from
Harrison D, Rubinfeld DL. Hedonic housing prices and the demand for Clean Air.
*Journal of Environmental Economics and Management*.
1978;5(1):81-102. doi:10.1016/0095-0696(78)90006-2. Unfortunately the article is
owned by Elsevier so I don't think I can get away
with putting the entire article in this repo.

Another suggested source is:
Belsley DA, Kuh E, Welsch RE. Regression Diagnostics. Identifying Influential
Data and Sources of Collinearity. New York, NY: Wiley; 1980. 
But I don't know why it's suggested, I haven't read it.

The codebook is mostly copied verbatim from a kaggle competition where the
link to the data no longer works:
https://www.kaggle.com/competitions/boston-housing/overview.
I reproduced it here since who knows how long that link will even work.

## Codebook

The variables listed in the data are:

* *crim*: per capita crime rate by town.
* *zn*: proportion of residential land zoned for lots over 25,00 sq.ft.
* *indus*: proportion of non-retail business acres per town.
* *chas*: Charles River indicator variable (1 if tract bounds river; 0
otherwise).
* *nox*: nitrogen oxides concentration (parts per 10 million).
* *rm*: average number of rooms per dwelling.
* *age*: proportion of owner-occupied units built prior to 1940.
* *dis*: weighted mean of distances to five Boston employment centers.
* *rad*: index of acessibility to radial highways.
* *tax*: full-value property-tax rate per $10,000.
* *ptratio*: pupil-teacher ratio by town.
* *black*: (1000)(Bk - 0.63)^2 where Bk is the proportion of Black people
living in a town. I have no idea why this specific transformation was used.
* *lstat*: lower status of the population (percent).
* *medv*: median value of owner-occupied homes in $1,000s.

## Suggested teaching uses

* Linear regression (response variable is *medv*, usually)
* Missing data imputation
* Clustering
* Some prediction models that are not too data-hungry like *k*-NN or regression trees.

<!-- END OF FILE -->
