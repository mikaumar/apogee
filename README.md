# Apogee

**Interactive Credit Risk Intelligence Platform**

28 modules covering institutional credit risk methodology — from foundational concepts to advanced quantitative frameworks.

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

## Features

- **Interactive calculators** — sliders drive real-time computation of EL, VaR, CVaR, DSCR, CVA, IFRS 9 staging, and more
- **Live visualisations** — loss distributions, ROC curves, survival curves, copula scatter plots, Monte Carlo histograms
- **Bayesian inference engine** — prior/posterior updates, MCMC diagnostics, sequential learning, SHAP decomposition
- **Stress testing suite** — scenario builder, reverse stress tests, Kessler cascade simulation
- **Self-contained** — single HTML file, no dependencies, runs offline

## Tech

Single `index.html` with inline CSS and JavaScript. No build step. No external dependencies.

- Canvas-based charts
- Beta-Binomial conjugate inference
- Metropolis-Hastings MCMC
- Vasicek one-factor portfolio model
- Gaussian and t-copula simulation

## Deployment

Served via GitHub Pages from the `master` branch.

---

Built by [SarynSpace](https://sarynspace.com)
