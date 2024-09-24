# lab 1.01

## Get general information about the dataset
> What is the measurement level (nominal, ordinal, interval, ratio) of each variable?

Is dit iets wat ik zelf hoor te verklaren? Ik weet niet of python dit zomaar kan weten van variabelen.

## Set qualitative variables as such
> For ordinal variables, also define a type and impose an order.

The only qualitative variables are as far as I can tell are sex and sport, and those both aren't ordinal. Are there no ordinal variables in the dataframe?

# lab 1.02
## Create contingency table with crosstab
> In this dataset, it is especially interesting to know how often each unique combination of `PersistenceType` and `DataSize` occurs. Figure out how to use the Pandas function `crosstab()` to create a so-called contingency table for these variables. By the way, this concept will return in Module 4 (examining the relationship between 2 qualitative variables).

Is `apc[['DataSize', 'PersistenceType']].value_counts()` niet ook goed?