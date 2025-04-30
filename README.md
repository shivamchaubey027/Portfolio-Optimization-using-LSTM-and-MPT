#  Portfolio Optimization using Python  


## Introduction

This repository is the culmination of my **Semester 6 Project** where I dove deep into the world of **financial portfolio optimization**. Coming from a Computer Science with AIML background, I wanted to challenge myself by applying **mathematical modeling, Python, and data science** to a real-world finance problem. This notebook is more than just code – it's a journey of learning, trial & error, and finally understanding the inner workings of modern portfolio theory.

---

## Problem Statement

**Objective:**  
To build a system that **optimizes a portfolio of stocks** using Python such that the **returns are maximized** for a given **level of risk**, or **risk is minimized** for a given return — using concepts from **Modern Portfolio Theory** (MPT) by Harry Markowitz.

---

##  Journey & Implementation

Initially, I was fascinated by how investors like Warren Buffet build portfolios. That curiosity led me to concepts like **expected returns, volatility, Sharpe ratio**, and **efficient frontiers**. I realized this would be a perfect intersection of Python, Data Science, and a practical problem.

### Step-by-Step Breakdown:

1. **Data Collection**  
   - Used `yfinance` to fetch historical stock prices.
   - Selected a basket of well-known stocks (like AAPL, MSFT, GOOG, etc.) for diversification.
   
2. **Calculating Returns & Covariance**  
   - Computed daily returns.
   - Derived mean returns and covariance matrix of the portfolio.
   
3. **Portfolio Simulation**  
   - Generated thousands of random portfolios with random weight allocations.
   - For each, computed expected return, volatility, and the Sharpe ratio.

4. **Optimization**  
   - Used `scipy.optimize` to **maximize the Sharpe ratio** and **minimize volatility**.
   - Applied constraints like sum of weights = 1 and individual weights between 0 and 1.

5. **Visualization**  
   - Plotted all simulated portfolios on a **risk-return scatter plot**.
   - Highlighted the **efficient frontier**, **maximum Sharpe ratio portfolio**, and **minimum volatility portfolio**.

---

## What I Learned
   - Real-world financial data handling with Python.
   - Portfolio theory and its mathematical basis.
   - Using `scipy.optimize` for constrained optimization.
   - Visualizing data using `matplotlib` and `seaborn`.
   - The balance between risk and reward in investments.
   - Clean and structured Jupyter Notebook documentation.

---

##  Tech Stack & Libraries

- **Python 3.10+**
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `yfinance`
- `scipy`

---


---


---

##  How to Run

1. **Clone this repository**  
   ```bash
   git clone https://github.com/yourusername/PortfolioOptimization.git
   cd PortfolioOptimization

2. **Run the notebook**

Open PortfolioOptimizationFinal.ipynb in Jupyter Notebook or VS Code.

---

## Future Scope
Add real-time stock data integration.

Support for cryptocurrencies and other asset classes.

Use machine learning to predict returns.

Add a simple Streamlit-based UI for non-technical users.

---

## Acknowledgements
Concepts inspired by Modern Portfolio Theory by Harry Markowitz.

Tutorials and blogs by QuantInsti, Investopedia, and various YouTube channels on Quant Finance.

---

##  Conclusion
This project taught me how theoretical finance meets practical Python programming.
It also gave me the confidence to work on multidisciplinary problems by blending coding, mathematics, and business logic.

I'm excited to expand on this in the future — maybe even build a full-fledged portfolio management tool someday!

Feel free to ⭐ this repo or suggest improvements via issues or pull requests.

Thanks for reading!
— Shivam Chaubey
