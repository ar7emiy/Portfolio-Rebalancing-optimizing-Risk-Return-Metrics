# Portfolio-Rebalancing-optimizing-Risk-Return-Metrics
Research Paper and final materials of the 3 month long capstone focusing on optimization of an individual portfolio
This rebalancing tool was integrated into InvestiGenie, an winning startup AI platform built during a FinTech Hackathon hosted by Morningstar.
*Note that the tool in the app was to show the ability of Retrieval Augmented Generation to explain complex statistical metrics for a proposed open-sourced library of Rebalancing tools.

# Brief Overview of Paper
In this paper, we explore the ability of various established risk metrics to enhance portfolio
rebalancing strategies by leveraging Monte Carlo Simulation and expanding on Efficient Frontier
analysis. The paper summarizes risk-return assessment of the best of thousands of portfolio
combinations across various sectors through analysis of advanced risk metrics and backtesting
on historical data. We seek to develop a portfolio optimization tool that allows for comparison of
Mean-Variance optimized portfolio and an equal weight portfolio against a portfolio allocation
computed using a composite of risk-return metrics. The results across the tested baskets of
stocks, which were picked from various industry sectors, yielded variable returns; some
extensively outperforming the S&P 500 benchmark and some not.

# Overview of Repo files

Note that each of the Ipynb files was used to rebalance and extract insights from various baskets of stocks. 
The only difference in each of the files is the list of stock tickers used and, therefore, the numerical and visual outputs

Q: Clear and unambiguous instructions on how to reproduce the predictions from start 
to finish including data pre-processing, feature extraction, model training and 
prediction generation. Point out the corresponding file names

A: To reproduce the results we have import all the packages listed in the requirements.txt. Open all the ipynb notebooks. And run all the cells. We use yfinance library to download all the required data into a variable so no additional files are required.


Q: Environment details regarding how the model was developed and trained, including 
OS, memory (RAM), disk space, CPU/GPU used, and any required environment 
configurations required to execute the code

A: No environment requirement are needed however the faster the runtime the faster the MC simulation will run. Hence we recommend to use a GPU for the reproduction of the code

Q: Data Files... Which data files are being used?

A: None. Each notebook retrieves data from yfinance library.

