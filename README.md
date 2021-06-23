# net_rate
shopee net_rate prediction

File name: net_rate
  
- Objective: predict tomorrow's net_rate
  
- Approach: one step ahead prediction models

File name: com_status_net_rate

use complete/(cancel+complete order) as net_rate

- Objective: predict future net_rate

- Approach: SES(one step), LSTM(one step), ARIMA(predict 15 days)
