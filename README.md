# Credit Risk Modeling and Simulation

In this project we are trying to model a credit-risky portfolio of corporate bonds. Using the data for 100 counterparties, we simulate 1-year losses for each corporate bond. 

3 sets of scenarios generated are - 
* `Monte Carlo approximation 1`: 5000 in-sample scenarios (N = 1000 x 5 = 5000 (1000 systemic scenarios and 5 idiosyncratic scenarios for each systemic), non-Normal distribution of losses)
* `Monte Carlo approximation 2`: 5000 in-sample scenarios (N = 5000 (5000 systemic scenarios and 1 idiosyncratic scenario for each systemic), non-Normal distribution of losses);
* `True distribution`: 100000 out-of-sample scenarios (N = 100000 (100000 systemic scenarios and 1 idiosyncratic scenario for each systemic), non-Normal distribution of losses).

The out-of-sample scenarios represent true distribution of portfolio losses. Two in-sample non- Normal datasets are used for evaluating sampling error and performing portfolio optimization.