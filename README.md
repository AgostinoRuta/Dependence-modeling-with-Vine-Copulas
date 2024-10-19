# Dependece Modeling with Vine-copula
This notebook estimates the percentage Value at Risk of an hypotetical portfolio of stocks. To do so, two different models are proposed.
While they both employ stationary bootstrapping to capture the time persistency, the first one joins the marginal samples through a 
gaussian copula and hence the sampling is derived through the inversion of the Sklaar's theorem. The second model instead builds a more
complex vine-structure to capture different dependence structures between the time series. 
