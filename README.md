# Stock Price Prediction Bank Jago Using Facebook Prophet Machine Learning & Python
## Overview
Bank Jago has attracted investors' attention since the end of December 2020, where previously the company was named **PT Bank Atos Indonesia Tbk**, then on 27 May 2021 based on ***the Decree of the Deputy Commissioner for Banking Supervision I OJK Number KEP-95/PB.1/2020 dated 27 may 2020 regarding the application of the use of a business license on behalf of PT Bank Artos Indonesia, Tbk to become PT Bank Jago, Tbk***.
this attracted the attention of investors because Bank Jago plans to **transform digital banks**, through this strategic planning since 2020, Bank Jago has become a concern for investors, where at the end of 2020 Bank Jago's share price was recorded at Rp 3,566. interestingly, **Gojek** through its subsidiary **PT Dompet Karya Anak Bangsa** acquired 1.95 billion shares of Bank Jago worth Rp 2.25 trillion on December 18, 2020.
Until now, the stock price of Bank Jago with the stock code "Arto" to be exact 12 November 2021 is worth Rp 15,500, meaning that since December 2020 there has been an increase of 334%.
To assess in helping investment decisions, are Arto's shares still attractive for investors to buy or will the price continue to increase?
For this reason, this program seeks to assist in predicting Arto's shares in making investment decisions, with the help of the `Facebook Prophet` and `Machine Learning`.
As reading material, you can read it through [Facebook Prophet](https://facebook.github.io/prophet/docs/quick_start.html) for time series predictions.

By using historical data obtained from [Yahoo Finance](https://finance.yahoo.com/quote/ARTO.JK/history?p=ARTO.JK), we can analyze what Bank Jago's stock price predictions will look like in the future.

## Results
### Plotting Using `Facebooks Prophet`
![Plot Arto](https://user-images.githubusercontent.com/91531966/141498668-04ff734c-b1f3-4281-8333-2e2a7c3f0dbb.png)

We can see, the results of the plot using `Facebook Prophet` show **good model results**, indicated by following the actual price line, we can also see that the plot results predict that Bank Jago shares will continue to increase, so this can be considered for investors as a signal buy, or for investors who already have it can continue to hold.

### Prediction results using a `Machine Learning`-based `Facebook Prophet` model
<img width="361" alt="Screenshot 2021-11-12 233458" src="https://user-images.githubusercontent.com/91531966/141501724-fca81c7c-25ea-446b-b531-8483426d8502.png">

If we see, the results of the model predictions are able to produce quite good insight.
