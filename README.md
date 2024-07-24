## Introduction

This project analyzes company registration statistics to understand market trends and economic conditions. By examining periods of high and low business activity, the insights gained assist in strategic planning and forecasting. This information is essential for businesses to align their strategies with market dynamics and for companies offering products or services to other businesses to assess their performance and market positioning.

![output.png](resources%2Foutput.png)

## Business Use Case

Understanding the impact of legal and regulatory changes on company registrations provides insights into how policy shifts influence business activity. Favorable changes, such as simplified registration processes or tax incentives, tend to boost new registrations. Conversely, stricter regulations or increased compliance costs can deter new business formations, resulting in a decrease in registrations.


![seasonality.png](resources%2Fseasonality.png)

## Model Evaluation

Several models were tested to predict company registrations, with the following results:

| Model                      | RMSE       | MAPE       |
|----------------------------|------------|------------|
| Default Model              | 2122.15    | 5.59%      |
| No Seasonality             | 2981.79    | 8.11%      |
| Add Quarterly Seasonality  | 1855.46    | 5.04%      |
| Multiplicative Seasonality | 2131.27    | 5.61%      |

## Predictions

![forecast.png](resources%2Fforecast.png)

Predictions for the next 6 months are as follows:

| Date       | Predicted | Predicted Lower | Predicted Upper |
|------------|-----------|-----------------|-----------------|
| 2024-06-30 | 29829.71  | 27151.01        | 32023.75        |
| 2024-07-31 | 31648.67  | 29328.66        | 34082.55        |
| 2024-08-31 | 32289.72  | 29958.91        | 34687.80        |
| 2024-09-30 | 34114.39  | 31736.04        | 36518.07        |
| 2024-10-31 | 30316.39  | 27899.38        | 32653.65        |
| 2024-11-30 | 25664.89  | 23404.88        | 27990.29        |

## Conclusion

The analysis highlights the importance of tracking company registration trends to understand market and regulatory impacts. The predictive models used provide valuable forecasts to assist in strategic decision-making.
