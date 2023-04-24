# spy_vix_sp20_predictions

The goal of this project is to forecast SPY returns based on machine-learning model. The dataset consists of daily closing prices for SPY and VIX.  SPY is the S&P500 ETF and VIX is a measure of the implied volatility of S&P500.  In addition, the dataset has a measure of the historical volatility of SPY.

The goal is to compare predictions over several time horizons. We focus on the next N trading days, with $N = 1$ and $N = 20$.

Based on the dataset provided, I chose to compare several methodologies and the corresponding results in the prediction of SPY returns. This report deals with two kind of approaches : first approach consists in prediction of SPY price from SPY price only, second one consists in the construction of different kind of features : VIX [1], SPY returns, shifted values for SPY and VIX and construction of indices such as MACD and RSI. [2]

Both approaches are tested with two kinds of neural network : a CNN based on the WaveNet Architecture and a LSTM Neural Network [3]

# Bibliography

*   [1] Hosker, James, et al. "Improving VIX futures forecasts using machine learning methods." SMU Data Science Review 1.4 (2018): 6.
*   [2] Rosillo, Rafael, Javier Giner, and David de la Fuente. "The effectiveness of the combined use of VIX and support vector machines on the prediction of S&P 500." Neural Computing and Applications 25.2 (2014): 321-332.
*   [3] : Samaha, Blake. "SPY Time Series Prediction". URL : https://github.com/bsamaha/SPY-Time-Series-Predictions
*   [4] Aguirre, Alberto Antonio Agudelo, Ricardo Alfredo Rojas Medina, and Néstor Darío Duque Méndez. "Machine learning applied in the stock market through the Moving Average Convergence Divergence (MACD) indicator." Investment Management & Financial Innovations 17.4 (2020): 44.

*   [5] Fernandon, Jason. "Relative Strength Index (RSI) Indicator Explained With Formula": URL = https://www.investopedia.com/terms/r/rsi.asp#:~:text=The%20relative%20strength%20index%20(RSI)%20is%20a%20momentum%20indicator%20used,the%20price%20of%20that%20security.&text=The%20RSI%20can%20do%20more%20than%20point%20to%20overbought%20and%20oversold%20securities.
*   [6] Daniel, Fabrice. "Financial Time Series Data Processing for Machine Learning." arXiv preprint arXiv:1907.03010 (2019).
*   [7] Johansson, Olof. "Stochastic modeling using machine learning and stochastic differential equations." (2022).