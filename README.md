# FYP-Portfolio-Management-System
# Machine Learning Based All Weather U.S. Stock Portfolio Management System
## Authors: YANG Wenting, CHO Hangsun, TAM Ching Lung, Ferdy

## Abstract

Nowadays more and more investors and traders are utilizing machine learning when generating trading ideas. This project aims to create a portfolio management on the stocks listed in the United State by incorporating different machine learning models via ensemble learning. In total, we implemented four different strategies using machine learning which are: Multi-factor stock selection model using LSTM and GRU, stock selection using Natural Language Processing models. Then, risk mitigation was done by calculating similarity scores and matrix using machine learning for the selected stocks. The best model of Multi-factor stock selection is GRU model trained with both technical and fundamental data, which  can achieve annualized return 24.2% and max drawdown 17.6%. The stock selection using Natural Language Process model able to filter out stocks with negative sentiment on its 10-K report, creating a more effective trade by holding the only necessary stocks and overall enhancing the strategy's return per trade and minimize the Max Drawdown when compared to a passive strategy that involves buying and holding the S&P 500 index. The stock selection using social media sentiment was able to extract sentiment and predict stocks and cryptocurrency prices using XGBoost, providing more diverse data sources and assets. The risk mitigation model removed similar stocks and created a new portfolio, which had 3 percentage points less in maximum drawdown and 8 percentage points less in return compared to the original portfolio. In the end the combined model had higher yearly return than that of the SPY, and outperformed SPY’s maximum drawdown by 7.3 percentage points.

## Model Design

![image](https://github.com/YanggWendy/FYP-Portfolio-Management-System/blob/main/design.png)

For more information, please refer to report: https://github.com/YanggWendy/FYP-Portfolio-Management-System/blob/main/Report/FYP%20Final%20Report.pdf
