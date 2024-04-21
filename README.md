# Bootstrapping-fundamentals

The process of bootstrapping is drawing small samples from a large sample of population (sampling with replacement) and estimating some quantity of the population by averaging estimates from multiple smaller samples.

Observations: 
1. By law of large numbers, mean of quantity estimated on smaller samples becomes close to mean of bigger sample as the size of smaller samples increases.
2. If the bigger sample is very large, then the quantity estimated on bigger sample is itself very close to that of actual population (By law of large numbers). Hence, the mean of quantity estimated on smaller samples gives a good estimate of that quantity in population itself. But, if the bigger sample size is small, then the estimation obtained from smaller samples is not close to that of population.
3. Increasing sample size improves the estimate of quantity on population.
4. Increasing number of bootstrapped samples improves the estimation of quantity on population.
5. Bagging is an implementation of bootstapping aggregation. It refers to averaging estimates of many small models obtained by training on different small samples to estimate a quantity on bigger sample.