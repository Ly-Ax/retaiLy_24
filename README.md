# GreenLy Tech

## Price Optimization with Machine Learning

[**Alex Castro Gumiel**](https://www.linkedin.com/in/alex-castro-gumiel/)

### Data Card

The dataset contains 9 variables and 100000 instances.

|Variable|Description|
|--------|-----------|
|isbn|ISBN code of the book|
|author|The name of the author of the book|
|title|The title of the book|
|genre|The list of genres related to the book|
|book_format|The format of the book|
|pages|Number of pages in the book|
|reviews|The number of reviews the book has|
|total_ratings|Total ratings of the book|
|rating|Average rating of the book|

https://www.kaggle.com/datasets/marian447/retail-store-sales-transactions

### Project Structure

    ├── data/
        └── raw/
            └── goodreads_books.csv                 -> Dataset with 100000 instances
        └── clean/
            └── goodreads_clean.csv                 -> Clean and transformed dataset
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
