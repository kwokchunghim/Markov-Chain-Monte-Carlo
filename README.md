# Markov-Chain-Monto-Carlo

In this project we implement, with R programming, two Markov Chain Monte Carlo (MCMC) Samplers, namely Metropolis Hastings Algorithm (M-H) and Slice Sampling [1]. 

In particular, we demonstrate the weakness of M-H algorithm when dealing with inference of multi-modal distributions as it easily gets stuck in one of the mode, lead to poor mixing.

On the contrary, we show that by using Slice Sampling, we can overcome this problem due to its robustness.

We implemented both samplers and compare their mixing performances on a multi-model posterior given by a flat uniform prior and cauchy likelihood with bi-modal observations.

For details please refer to the report.


Reference:
[1] Neal, R. M. (2003). Slice sampling. The Annals of Statistics, 31(3). https://doi.org/10.1214/aos/1056562461 
