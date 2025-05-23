# 📊 Quantitative Finance Research Implementations

This repository contains my implementations and backtesting efforts for a growing collection of quantitative finance research papers. Each paper is implemented from scratch or restructured using Python, with a strong focus on reproducibility, clarity, and educational value.

The goals of this project are:

- To deepen my understanding of mathematical models and methods used in quantitative finance  
- To validate and extend existing research through code  
- To share practical, readable implementations for students, researchers, and practitioners

---

## 📚 Papers Implemented

### 1. **Empirical Analysis of Value at Risk (VaR) of Stock Portfolio Based on Python**  
**Author**: Shengyuan Lu  
**Description**: This paper examines Value at Risk (VaR) for equity portfolios using Python. I’ve replicated the parametric, historical simulation, and Monte Carlo methods for VaR estimation. Comparative analysis and visualization are included.  
**Keywords**: VaR, Monte Carlo Simulation, Risk Management, Portfolio Analysis  

➡️ [View Implementation](https://github.com/Jeetmu/Empirical-Analysis-of-Value-at-Risk-VaR-of-Stock-Portfolio)

---

### 2. **Arbitrage-Free Smoothing of the Implied Volatility Surface**  
**Author**: Matthias Fengler  
**Description**: The paper introduces a non-parametric arbitrage-free approach for estimating the implied volatility surface using constrained smoothing techniques. I’ve implemented a natural cubic spline smoothing algorithm with no-arbitrage constraints from scratch, along with IV surface construction.  
**Keywords**: Implied Volatility, Spline Smoothing, No-Arbitrage Conditions, Derivatives Pricing  

➡️ [View Implementation](https://github.com/Jeetmu/Arbitrage-free-smoothing-of-the-implied-volatility-surface)

---

### 3. **Reconstructing the Local Volatility Surface from Market Option Prices**
**Institution**: Department of Mathematics, Korea University  
**Description**: This paper presents a robust method for reconstructing the local volatility surface by solving an inverse problem based on market option prices. The local volatility function is inferred by minimizing the difference between theoretical and observed prices using a finite difference method on the generalized Black–Scholes PDE.  
**Keywords**: Local Volatility, Inverse Problems, Finite Difference Method, Option Pricing

➡️ [View Implementation](https://github.com/Jeetmu/local_volatility_model)

---

### 4. **Gaussian Processes for Implied Volatility Estimation**
**Institution**: Stevens Institute of Technology  
**Description**: This paper introduces a Bayesian nonparametric approach using Gaussian Processes (GP) to estimate the implied volatility surface with uncertainty quantification. By incorporating temporal dynamics, the model captures the evolution of the surface over time and demonstrates improved accuracy over traditional parametric methods. Empirical validation and hedging simulations highlight the practical benefits of this approach.  
**Keywords**: Implied Volatility, Gaussian Processes, Bayesian Inference, Machine Learning, Option Pricing

➡️ [View Implementation](https://github.com/Jeetmu/Gaussian-Process-for-IVS)

---

## 🧠 About Me

I am a Master's student in Financial Engineering and Applied Mathematics with a passion for quantitative modeling and research replication. This repository is part of my long-term effort to understand and build models grounded in both theory and practice.

Feel free to connect on [LinkedIn](https://www.linkedin.com/in/geet-mukherjee/) or open an issue for collaboration!
