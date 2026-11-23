# Forecasting US Candy Production

Final project for a business forecasting course. It forecasts the monthly US candy production index for September 2026 – August 2027 using the Federal Reserve's industrial production index for sugar and confectionery products (FRED series IPG3113N, January 1972 – August 2026).

Six models were compared on RMSE: seasonal naive, Holt-Winters, ETS, STL + ETS, seasonal ARIMA and regression. The recommended model, seasonal ARIMA(3,0,0)(1,1,1)[12], forecasts an average index of 84.3 for the next 12 months, 4.8% below the last 12 months.

## Files

| File | Description |
|---|---|
| `Candy_Forecast_Presentation.pptx` | Presentation for the class |
| `Candy_Forecast_Management_Memo.docx` | One-page memo for management |
| `Candy_Final_Project.Rmd` | R code for the full analysis |
| `candy.csv` | Data (Jan 1972 – Aug 2026) |

To run the analysis, put `candy.csv` in the same folder as the Rmd and click **Knit** in RStudio (requires the `fpp2` and `forecast` packages).
