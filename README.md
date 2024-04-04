# GreenLy Tech

## Retail Machine Learning Lab

[**Alex Castro Gumiel**](https://www.linkedin.com/in/alex-castro-gumiel/)

### Data Card

The dataset contains 16 variables and 9994 instances.

|Variable|Description|
|--------|-----------|
|Order ID|Unique order ID for each customer|
|Order Date|Order date of the product|
|Ship Date|Shipping date of the product|
|Ship Mode|Shipping mode specified by the customer|
|Segment|The segment where the customer belongs|
|Country|Country of residence of the customer|
|Region|Region where the customer belong|
|State|State of residence of the customer|
|City|City of residence of of the customer|
|Customer Name|Name of the customer|
|Category|Category of the product ordered|
|Sub-Category|Sub-Category of the product ordered|
|Product Name|Name of the product|
|Sales|Sales of the product|
|Quantity|Quantity of the product|
|Profit|Profit / loss incurred|

Based and sampled from [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

### Project Structure

    ├── data/
        └── raw/
            └── sample_superstore.csv               -> Original superstore dataset
        └── clean/
    ├── notebooks/
        └── data_exploration.ipynb                  -> Exploratory Data Analysis
        └── preprocessing.ipynb                     -> Data Preprocessing
    ├── src/
        └── transform/
            └── __init__.py                         -> Convert directory to package
        └── transform_main.py                       -> Dataset transformation
    ├── .gitignore                                  -> Ignored files and folders
    ├── LICENSE                                     -> Open source license
    ├── README.md                                   -> Information about the project
    ├── requirements.txt                            -> Necessary library versions
