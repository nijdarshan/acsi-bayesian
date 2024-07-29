# Customer Satisfaction and Loyalty: Analyzing Pricing Dynamics Using ACSI Data

## Project Overview

This project explores the complex relationships between customer satisfaction, perceived value, loyalty, and price tolerance using the American Customer Satisfaction Index (ACSI) dataset. By leveraging structure learning algorithms, I aim to identify key drivers of customer loyalty and provide actionable insights for strategic customer relationship management.

## Dataset

The dataset used in this project is the ACSI dataset from 2015, which includes measures of customer expectations, satisfaction, loyalty, and demographics across various sectors such as food, airlines, ISPs, and banking.

## Research Questions

The study aims to answer the following questions:
1. How does perceived value impact customer satisfaction and loyalty?
2. What role does price tolerance play between customer satisfaction and loyalty?
3. What is the impact of demographic factors on customer satisfaction and loyalty?

## Methodology

### Structure Learning Algorithms

Several structure learning algorithms were applied to the dataset:
- Hill Climbing (HC)
- Tabu Search (TABU)
- SaiyanH
- Max-Min Hill Climbing (MAHC)
- Greedy Equivalence Search (GES)

### Knowledge-Based Approach

The foundational model for this research is inspired by Professor Claes Fornell's ACSI model, which captures interactions between customer expectations, perceived quality and value, satisfaction, complaints, and loyalty.

## Results

The results were analyzed based on CPDAG scores, log-likelihood (LL) scores, and Bayesian Information Criterion (BIC) scores. The findings indicate varying degrees of accuracy and model complexity across different algorithms.

### Key Findings

- **Perceived Value and Customer Loyalty**: Higher perceived value tends to enhance customer loyalty, with price tolerance acting as a significant mediator.
- **Demographic Impact**: Age, income, and education levels distinctly affect customer expectations and perceptions, influencing their overall satisfaction and loyalty.
- **Algorithm Performance**: The HC and GES algorithms showed competitive F1 scores, indicating effective capture of the data's underlying structure. In contrast, the SaiyanH and MAHC algorithms exhibited lower scores, suggesting potential overfitting and complexity issues.

## Conclusion

The integration of domain knowledge with structure learning algorithms provides a nuanced understanding of customer satisfaction dynamics. Businesses can leverage these insights to develop targeted strategies for improving customer loyalty.

## References

1. Fornell, Claes, et al. “The American Customer Satisfaction Index: Nature, Purpose, and Findings.” Journal of Marketing, vol. 60, no. 4, 1996, pp. 7–18. [JSTOR](https://doi.org/10.2307/1251898).
2. Hult, G.T.M., Morgeson, F.V., Morgan, N.A., et al. “Do managers know what their customers think and why?” Journal of the Academy of Marketing Science, vol. 45, no. 1, 2017, pp. 37–54. [Springer](https://doi.org/10.1007/s11747-016-0487-4).
3. Hult, Tomas; Morgeson, Forrest (2023). “The American Customer Satisfaction Index (ACSI): A Sample Dataset and Description”, Mendeley Data, V2. [Mendeley Data](https://doi.org/10.17632/64xkbj2ry5.2).

