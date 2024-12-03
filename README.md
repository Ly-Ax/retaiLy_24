[<img align="right" src="images/greenly_tech.png" width="200px">](https://greenlytech.com/)

# greenLy: Retail

[Alex Castro Gumiel](https://www.linkedin.com/in/alex-castro-gumiel/)
<!-- [Mireya Quinteros Hernandez](https://www.linkedin.com/in/mireyaquinteros/) -->
[**GreenLy Tech**](https://greenlytech.com/)

## Use Case: Store Sales

<!-- The dataset contains 11 variables and 149116 instances. -->

|Variable|Description|
|--------|-----------|
<!-- |transaction_id|Transaction ID|
|transaction_date|Date of transactions|
|transaction_time|Time of transactions|
|store_location|The location of store|
|product_category|The category of product|
|product_type|The type of product|
|product_detail|The product name|	
|product_size|The size of product|
|unit_price|Product price per unit|
|quantity|Product quantity|
|total_bill|The total bill| -->

[Retail Store Sales Transactions](https://www.kaggle.com/datasets/marian447/retail-store-sales-transactions)

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
