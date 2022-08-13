# Equation of Lake Burley Griffin

The probability of Canberra suburb $i$ being on the northside is defined as:

$$ P_i = \left( {1 + exp \left[ {\beta_0 + \sum_{j=1}^5 \beta_j X_{ij} + \sum_{j=1}^5 \gamma_j X_{ij}^2} \right]} \right)^{-1} $$

where:

- $\beta_0 \approx -151.1$
- $\beta_j \approx \left[ -10.0, -496.5, -490.8, 510.3, 402.7 \right]$
- $\gamma_j \approx \left[ 289.7, 663.0, 494.1, -213.6, -490.8 \right]$
- $X_i$ is a set of relative, weighted proportions $\left( 0 \rightarrow 1 \right)$ of residents in suburb $i$ such that:
    - $X_{i1}$ = residents born in Vietnam
    - $X_{i2}$ = residents who are secular
    - $X_{i3}$ = residents aged under 25
    - $X_{i4}$ = residents who earn less than $3,000 a week
    - $X_{i5}$ = residents born in China

You can see how this equation is applied [on the ABC News website](https://www.abc.net.au/news/2022-08-10/census-reveals-canberras-changes-and-differences/101267070).    
