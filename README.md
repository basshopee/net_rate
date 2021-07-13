# net_rate
shopee net_rate prediction

File name: com_status_net_rate

- Net_rate: complete/(cancel+complete order)

- Objective: predict future net_rate

- Approach: SES(one step), LSTM(one step), ARIMA(predict 30 days), Holt Winters(predict 30 days), Random Forest(one step), SARIMAX(predict 30 days): use GMV as exogenous factor
