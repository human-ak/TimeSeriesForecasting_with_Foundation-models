Backtesting popular Foundation models developed by Salesforce, Google, IBM, & Amazon that supports zero shot forecasting.

Datasets: Gold (GC=F), Crude Oil (CL=F), & S&P 500 (^GSPC) between the period 01-01-2001 to 30-04-2024 soucred from Yahoo Finance

Backtests: 2 year walk forward validation

In each forecasting iteration we forecast for the next 12 months.


| Salesforce Moirai | Avg. MAPE | Std.Dev. of Avg. MAPE | Avg. sMAPE | Std.Dev. of Avg. sMAPE | Avg. MSE   | Std.Dev. of Avg. MSE | Avg. MAE | Std.Dev. of Avg. MAE |
|-------------------|-----------|------------------------|------------|-------------------------|------------|------------------------|----------|------------------------|
| Gold (GC=F)        | 13.11     | 7.01                   | 13.69      | 8.07                    | 155.65     | 135.83                 | 10.13    | 5.60                   |
| Crude Oil (CL=F)   | 11.26     | 4.28                   | 12.31      | 4.87                    | 126371.39  | 76557.99               | 278.74   | 118.61                 |
| S&P 500 (^GSPC)    | 8.51      | 3.04                   | 9.04       | 3.37                    | 289118.98  | 170915.45              | 451.09   | 154.07                 |



| Google TimesFM | Avg. MAPE | Std.Dev. of Avg. MAPE | Avg. sMAPE | Std.Dev. of Avg. sMAPE | Avg. MSE   | Std.Dev. of Avg. MSE | Avg. MAE | Std.Dev. of Avg. MAE |
|-------------------|-----------|------------------------|------------|-------------------------|------------|------------------------|----------|------------------------|
| Gold (GC=F)        | 7.98      | 2.06                   | 7.93       | 1.91                    | 53.65      | 24.96                  | 6.08     | 1.45                   |
| Crude Oil (CL=F)   | 20.54     | 8.33                   | 23.97      | 10.38                   | 371252.01  | 235903.49              | 503.96   | 226.51                 |
| S&P 500 (^GSPC)    | 11.22     | 1.94                   | 12.10      | 2.20                    | 492725.22  | 160837.08              | 604.94   | 121.81                 |