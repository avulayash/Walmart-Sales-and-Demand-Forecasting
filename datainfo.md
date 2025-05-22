## Resources

For this project, the **Walmart Sales Dataset** was used from the open-source data repository [Kaggle](https://www.kaggle.com), which holds the historical sales of 45 Walmart stores[^3]. It contains data on holiday event sales trends around **Super Bowl**, **Labour Day**, **Thanksgiving**, and **Christmas**.

The dataset includes **6,435 records** and **8 attributes** that capture key information about store-level sales, holiday indicators, weather conditions, fuel prices, and economic factors.

### Table 1: Walmart Sales Dataset Attributes

| Attribute       | Description                                                                 | Data Type      |
|----------------|-----------------------------------------------------------------------------|----------------|
| `Store`         | Unique identifier for each store.                                            | Integer        |
| `Date`          | Weekly timestamp representing the week-ending date.                         | Object (Date)  |
| `Weekly_Sales`  | Total sales for the week at the store level.                                | Float          |
| `Holiday_Flag`  | Indicates if the week includes a major holiday (`1 = Holiday`, `0 = Non-Holiday`). | Integer    |
| `Temperature`   | Average temperature during the week (in Fahrenheit).                        | Float          |
| `Fuel_Price`    | Cost of fuel during the week (per gallon).                                  | Float          |
| `CPI`           | Consumer Price Index, an economic indicator.                                | Float          |
| `Unemployment`  | The unemployment rate for the store's region during the week.               | Float          |

[^3]:https://www.kaggle.com/datasets/rutuspatel/retail-analysis-with-walmart-sales-data
