<img align="right" src="images/greenly_tech.png" width="200px">

# GreenLy: Retail ML Lab

[**Alex Castro Gumiel**](https://www.linkedin.com/in/alex-castro-gumiel/)

<!-- [**Mireya Quinteros Hernandez**](https://www.linkedin.com/in/mireyaquinteros/) -->

## Data Card

The dataset contains 17 variables and 51290 instances.

|Variable|Description|
|--------|-----------|
|Order ID|Unique order ID for each customer|
|Order Date|Order date of the product|
|Order Priority|Order priority of the product|
|Ship Date|Shipping date of the product|
|Ship Mode|Shipping mode specified by the customer|
|Segment|The segment where the customer belongs|
|Market|The market where the customer belongs|
|Country|Country of residence of the customer|
|State|State of residence of the customer|
|City|City of residence of of the customer|
|Customer Name|Name of the customer|
|Category|Category of the product ordered|
|Sub-Category|Sub-Category of the product ordered|
|Product Name|Name of the product|
|Sales|Sales of the product|
|Quantity|Quantity of the product|
|Profit|Profit / loss incurred|

Based and sampled from [Kaggle - Superstore Data](https://www.kaggle.com/datasets/jr2ngb/superstore-data)

## Project Structure

    ├── data/
        └── raw/
            └── superstore_data.csv                 -> Sampled superstore dataset
        └── clean/
    ├── images/
        └── greenly_tech.png                        -> GreenLy Tech main image
    ├── notebooks/
        └── methodology/
            └── crisp_ml_retail.ipynb               -> CRISP-ML(Q): Retail ML Lab
        └── transform/
            └── data_exploration.ipynb              -> Exploratory Data Analysis
            └── preprocessing.ipynb                 -> Data Preprocessing
    ├── src/
        └── transform/
            └── __init__.py                         -> Convert directory to package
        └── transform_main.py                       -> Dataset transformation
    ├── .gitignore                                  -> Ignored files and folders
    ├── LICENSE                                     -> Open source license
    ├── README.md                                   -> Information about the project
    ├── requirements.txt                            -> Necessary library versions
