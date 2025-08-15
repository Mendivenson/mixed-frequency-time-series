# Mixed-Frequency Time Series Analysis

This repository explores **mixed-frequency** time series analysis, starting with the implementation and study of the paper:

> [**"A new coincident index of business cycles based on monthly and quarterly"**](https://economics.sas.upenn.edu/pier/working-paper/2002/new-coincident-index-business-cycles-based-monthly-and-quarterly-series)
> Mariano, R. S., & Yasumoto, T.

The main goal is to **develop all code from scratch in R**, avoiding the use of packages that already implement the **Kalman filter** or provide high-level time series handling functions, in order to fully understand every mathematical and computational step.

---

## 🎯 Goals

- Reproduce and understand mixed-frequency models.
- Implement **time series factor analysis**.
- Build and implement the **Kalman filter** and smoothing manually.
- Apply methods to real macroeconomic data.
- Document each step of the mathematical and computational process.

---

## 📚 Methodology

1. Theoretical study of Mariano & Yasumoto’s paper.
2. Mathematical formulation of the mixed-frequency factor model.
3. Manual implementation of the Kalman filter (prediction and update steps).
4. Simulation and validation with synthetic data.
5. Application to real-world datasets.

---

## 🛠️ Technologies & Tools

- **Language:** R

---

## 🗺️ Roadmap

### Phase 1 — Paper Analysis
- [ ] Read and summarize Mariano & Yasumoto (2002).
- [ ] Extract key equations, model structure, and assumptions.
- [ ] Document the role of mixed-frequency data in the proposed coincident index.

### Phase 2 — Method Implementation
- [ ] Formulate the state-space representation described in the paper.
- [ ] Implement the Kalman filter and smoothing from scratch in R.
- [ ] Estimate model parameters using Maximum Likelihood.
- [ ] Apply the model to real macroeconomic data and interpret results.
