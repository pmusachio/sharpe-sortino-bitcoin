![Badge](https://img.shields.io/badge/Status-Completed-green)
# Sharpe vs Sortino W/ Bitcoin 
Analyze and compare the performance of Sharpe and Sortino Ratio using Bitcoin data, demonstrating their differences under different market conditions

</br>

## About the Data
- Bitcoin (BTCUSD) historical data (2018~2025) using YFinance

</br>

## Data Preparation
- Calculating Sharpe and Sortino Ratio using QuantStats

</br>

## Modeling
- Applying logarithmic transformation to Bitcoin prices
- Calculating Sharpe and Sortino Ratio in rolling intervals

</br>

## Evaluation
Correlation analysis between Sharpe and Sortino


- Sortino is best suited to assess performance in high volatility markets
- Sharpe is most sensitive to overall volatility, including positive movements

</br>

## Deployment
- Show results in a Jupyter notebook

</br>

## How to Run
```bash
git clone https://github.com/pmusachio/sharpe-sortino-bitcoin.git

cd enterYourDownloadPath/sharpe-sortino-bitcoin

python -m venv venv
source venv/bin/activate

pip install -r requirements.txt
```

</br>

## Get in touch
[![Gmail](https://img.shields.io/badge/paulomusachio@gmail.com-white?logo=gmail)](mailto:paulomusachio@gmail.com) </br>
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pmusachio-blue)](https://www.linkedin.com/in/pmusachio/)
