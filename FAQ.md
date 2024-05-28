---
title: 'FAQ'
---

**What is Genesis’ underlying model architecture?**

While Genesis is proprietary, the underlying architecture is essentially two models. One which is a mathematical model which is used to calculate directional volatility based on open, high, low and close prices which gives us a proprietary volatility dataset. The second being a transition probability model which utilises the volatility dataset to model the time-varying probabilities between volatility states. 

**What data was used to train the model?** 

The model was trained using proprietary volatility data derived from the S&P 500 daily price data from 2000 to 2021. To enhance the model's robustness, additional synthetic volatility data generated in-house was used for further training.

**What is the minimum time periods Genesis needs to start forecasting?**

Genesis requires a minimum of 15-20 complete OHLC time periods to start forecasting, however we recommend at least 400 complete OHLC time periods to understand the context of the underlying time series. 

**What asset classes can Genesis be applied to?**

- Bonds 
- Commodities
- Cryptocurrencies 
- Derivatives
- Equities
- Indices 
- FX 

**What are Genesis’ data inputs?** 

- Datetime (YYYY-MM-DD HH:MM:SS)
- Open Price (Float)
- High Price (Float)
- Low Price (Float)
- Close Price (Float)

**What are Genesis’ outputs?**

- Price trend forecast (int)
- Risk forecast (float)

**Can Genesis quantify the risk associated with each forecast?**

Genesis provides an associated risk forecast with each price trend forecast. The risk forecast represents the expected range the price will stay within for the forecasted period. If price moves outside the price boundary, it signals a potential change in price trend that can be confirmed by analysing a shorter time horizon.

**Can Genesis handle multiple time series?** 

Genesis can currently only hand univariate time series. 

**Can Genesis forecast multiple steps ahead?**

Genesis can currently only forecast one-step ahead.

**Can Genesis handle irregular time stamps?**

Genesis can handle financial time series with irregular timestamps (format: YYYY-MM-DD HH:MM:SS).

**Is Genesis open source?** 

Genesis is currently closed source. 

**How can I use Genesis?** 

Contact us to request a free two-week trial – hello@sumtyme.ai 
