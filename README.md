# Apogee

**Interactive Credit Risk Intelligence Platform**

38 modules covering institutional credit risk methodology — from foundational concepts through Bayesian inference to frontier research.

**[Launch Apogee →](https://mikaumar.github.io/apogee/)**

---

## Modules

### I · Foundations
1. What Is Credit Risk
2. The Core Formula (EL = PD × LGD × EAD)
3. Probability of Default

### II · Components
4. Loss Given Default
5. Exposure at Default
6. Expected vs Unexpected Loss

### III · Models
7. Structural Models (Merton)
8. Reduced-Form Models (Hazard Rates)
9. Machine Learning Approaches

### IV · Application
10. Credit Ratings
11. Portfolio & Correlation
12. Full Risk Calculator

### V · Bayesian Framework
13. Why Bayesian
14. Prior Specification
15. Likelihood Function
16. Posterior Update
17. MCMC Sampling
18. PD Output & Credible Intervals
19. Sensitivity & SHAP
20. ALPHA Architecture

### VI · Advanced
21. Knowledge Map
22. Monte Carlo Simulation
23. Copula Models
24. Stress Testing & Reverse Stress
25. CVA / XVA
26. IFRS 9 Deep Dive
27. Model Validation
28. Credit Derivatives & Sovereign

### VII · Regulatory & Capital
29. Basel III/IV Capital Rules
30. Credit Migration Matrices
31. Concentration Risk

### VIII · Counterparty & Transfer
32. Wrong-Way Risk
33. Economic Capital Allocation
34. Credit Risk Transfer

### IX · Frontier
35. Climate Credit Risk
36. Network & Contagion Models
37. Deep Learning for PD
38. Kessler Cascade Modelling

## Features

- **Interactive calculators** — sliders drive real-time computation of EL, VaR, CVaR, DSCR, CVA, IFRS 9 staging, IRB capital, HHI, and more
- **Live visualisations** — loss distributions, ROC curves, survival curves, copula scatter plots, Monte Carlo histograms, Lorenz curves, network graphs, cascade simulations
- **Bayesian inference engine** — prior/posterior updates, MCMC diagnostics, sequential learning, SHAP decomposition
- **Stress testing suite** — scenario builder, reverse stress tests, Kessler cascade simulation
- **Regulatory coverage** — Basel III/IV IRB formula, credit migration matrices, concentration risk, SRT tests
- **Frontier research** — climate credit risk, network contagion (DebtRank), deep learning PD, orbital debris cascade
- **Self-contained** — single HTML file, no dependencies, runs offline

## Tech

Single `index.html` with inline CSS and JavaScript. No build step. No external dependencies.

- Canvas-based charts and visualisations
- Beta-Binomial conjugate inference
- Metropolis-Hastings MCMC
- Vasicek one-factor portfolio model
- Gaussian and t-copula simulation
- Euler capital allocation
- DebtRank network contagion
- Kessler cascade simulation

## Deployment

Served via GitHub Pages from the `master` branch.

---

Built by [SarynSpace](https://sarynspace.com)
