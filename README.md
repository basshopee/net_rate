# net_rate
shopee net_rate prediction

File name: net_rate_no_lstm_07jul21_nocut_upload
- Data from 2015-05-25 to 2021-07-07

- Net_rate: complete/(cancel+complete order)

- Objective: predict future net_rate

- Approach: SES(one step), ARIMA(predict 30 days), Holt Winters(predict 30 days), Random Forest(one step), SARIMAX(predict 30 days): use GMV as exogenous factor
