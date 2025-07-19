# Cryptocurrencies_Copula_RiskModeling
Quantitative analysis of the dependency structure between Bitcoin and Ethereum using copula models and Monte Carlo simulations. Developed as part of an assignment project for the Risk Measurement 1 module in the BCom Honours in Quantitative Finance program at the University of Johannesburg.

## 🎯 Objectives
- Identify stylized facts of Bitcoin and Ethereum log-returns, focusing on heavy tails, volatility clustering, and distributional characteristics.
- Evaluate the dependency structure between Bitcoin and Ethereum log-returns by fitting Gaussian and Student-t copulas, guided by scatterplot insights and formally assessed using AIC and BIC for copula selection.
- Visualize dependence structures and tail behavior
- Assess how the copula-based dependency insights differ from conventional correlation measures, highlighting the limitations of linear correlation in capturing joint tail events and non-linear co-movements.
- Evaluate whether the Student-t copula structure provides meaningful predictability for future price co-movements between Bitcoin and Ethereum, particularly in high-volatility regimes, based on observed dependence patterns.
- Analyze asymmetric tail dependence between Bitcoin and Ethereum using copula modeling, focusing on how sudden price surges or crashes in one asset influence the other.
- Evaluate the likelihood and intensity of joint price increases versus joint price crashes between Bitcoin and Ethereum using copula-based Monte Carlo simulations. Tail dependence was assessed by calculating joint probabilities for extreme gains and losses, uncovering asymmetric risk dynamics and potential contagion effects.
- Propose trading and hedging strategies for cryptocurrency portfolios based on tail dependence dynamics and non-linear joint behavior captured by the fitted copula models.

## 📊 Dataset
Daily closing prices for Bitcoin and Ethereum were provided in an Excel file (crypto_prices.csv) as part of the Risk Measurement 1 assignment. The data spans from **January 3, 2020 to December 30, 2023**, and includes BTC-USD and ETH-USD prices used to compute log-returns for dependency modeling.

## 🧠 Tools Used
- **Python** (Pandas, NumPy, Matplotlib, SciPy,statsmodels)
- **copulas** library for fitting and sampling dependency models
- **Jupyter Notebook** for interactive analysis and visualization

## 📈 Key Findings
- BTC and ETH exhibit heavy tails and volatility clustering.
- Scatterplots show moderate co-movement in normal conditions, with weak tail dependence.
- Student-t copula outperformed Gaussian copula based on AIC and BIC.
- Monte Carlo simulations revealed joint crashes are slightly more probable than joint gains.
- Asymmetric risk dynamics suggest potential contagion during stress events.

## 💼 Investment Implications
The copula-based analysis shows joint crashes between BTC and ETH are slightly more probable than joint gains, highlighting asymmetric tail risk. Investors can consider hedging via forward contracts, seek arbitrage during price divergence, use spread strategies for downside protection, and deploy combination strategies like straddles to capitalize on volatility.

## 📝 Conclusion
This project provides a robust framework for understanding dependency structures between cryptocurrencies. Through copula modeling and simulation-based tail analysis, it highlights how traditional correlation metrics may underestimate risk-especially during market extremes. The insights support more resilient portfolio construction and stress-aware trading strategies.

## ▶️ How to Run
- Clone the repository
- Open 220036766_SEEPAMORE_MO_RMO8X01_ASSIGNMENT1_2025.ipynb in Jupyter
- Run all cells to execute the full analysis — from stylized facts, GARCH modeling, copula fitting, to Monte Carlo simulations

## 📂 Included Files
- 220036766_SEEPAMORE_MO_RMO8X01_ASSIGNMENT1_2025.ipynb – Full notebook with dependency modeling.
- crypto_prices.csv – Excel dataset containing daily BTC and ETH prices from Jan 2020 to Dec 2023, used to compute log-returns for analysis.

## 👤 Author
**Student Name**: Onthatile Seepamore  
**Student Number**: 220036766  
**Course**: BCom Honours in Quantitative Finance  
**Institution**: University of Johannesburg  
**Year**: 2025
