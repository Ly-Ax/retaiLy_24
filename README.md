<img align="right" src="images/greenly_tech.png" width="200px">

# GreenLy: Retail ML

[**Alex Castro Gumiel**](https://www.linkedin.com/in/alex-castro-gumiel/)

## Use Case: Coffee Shop Sales

The dataset contains 11 variables and 149116 instances.

|Variable|Description|
|--------|-----------|
|transaction_id|Transaction ID|
|transaction_date|Date of transactions|
|transaction_time|Time of transactions|
|store_location|The location of store|
|product_category|The category of product|
|product_type|The type of product|
|product_detail|The product name|	
|product_size|The size of product|
|unit_price|Product price per unit|
|quantity|Product quantity|
|total_bill|The total bill|

[Kaggle - Coffee Shop Sales](https://www.kaggle.com/datasets/divu2001/coffee-shop-sales-analysis)

## Final Project Structure

    ├── data/
        └── raw/
            └── coffee_shop_sales.csv               -> Coffee Shop sampled dataset
        └── clean/
            └── coffee_shop_clean.csv               -> Coffee Shop clean dataset
            └── coffee_shop_train.csv               -> Coffee Shop train dataset
            └── coffee_shop_test.csv                -> Coffee Shop test dataset
    ├── images/
        └── ...                                     -> Multiple project images
    ├── models/
        └── coffee_transform.joblib                 -> Coffee Shop data pipeline
    ├── notebooks/
        └── methodology/
            └── ml_operations.ipynb                 -> Machine Learning Operations
            └── crisp_ml_retail.ipynb               -> CRISP-ML(Q): Retail ML Lab
        └── analysis/
            └── coffee_shop_eda.ipynb               -> Coffee Shop Sales EDA
        └── transform/
            └── coffee_pipeline.ipynb               -> Coffee Shop data pipeline
        └── time_series/
            └── ...                                 -> 
    ├── src/
        └── transform/
            └── __init__.py                         -> Convert directory to package
        └── transform_main.py                       -> Dataset transformation
    ├── .gitignore                                  -> Ignored files and folders
    ├── LICENSE                                     -> Open source license
    ├── README.md                                   -> Information about the project
    ├── requirements.txt                            -> Necessary library versions
