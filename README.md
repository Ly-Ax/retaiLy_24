[<img align="right" src="images/greenly_tech.png" width="200px">](https://greenlytech.com/)

# greenLy: Retail ML Lab

[Alex Castro Gumiel](https://www.linkedin.com/in/alex-castro-gumiel/)

## Use Case: Retail Store Sales Transactions

The dataset contains 7 variables and 131706 instances.

|Variable|Description|
|--------|-----------|
|Date|Sales date|
|Transaction|Transaction ID|
|Customer|Customer code|
|Category|Category code|
|Product|Poduct code|
|Quantity|Sales quantity|
|SalesAmount|Sales amount|

[Scanner Data](https://www.kaggle.com/datasets/marian447/retail-store-sales-transactions)

## Project Structure

    ├── data/
        └── raw/
            └── scanner_sales.csv                -> Scanner Sales raw dataset
    ├── images/
        └── ...                                  -> Multiple project images
    ├── notebooks/
        └── methodology/
            └── ml_operations.ipynb              -> Machine Learning Operations
            └── crisp_ml_retail.ipynb            -> CRISP-ML(Q): Retail ML Lab
        └── analysis/
            └── scanner_sales_eda.ipynb          -> Scanner Sales data analysis
        └── transform/
            └── scanner_pipeline.ipynb           -> Scanner Sales data pipeline
        └── time_series/
            └── arima_prophet.ipynb              -> ARIMA and Prophet Models
            └── var_model.ipynb                  -> 
            └── rnn_time_series.ipynb            -> 
    ├── src/
        └── transform/
            └── __init__.py                      -> Convert directory to package
    ├── .gitignore                               -> Ignored files and folders
    ├── LICENSE                                  -> Open source license
    ├── README.md                                -> Information about the project
    ├── requirements.txt                         -> Necessary library versions
