
# Book Recommendation Website using collaborative filtering

This website can predict similar books based on collaborative filtering


## Overview of the website

### Homepage

![home](https://github.com/shadow-1310/book_recommendation_system/blob/main/README_images/homepage.png)

### datalist options to select 

![datalist](https://github.com/shadow-1310/book_recommendation_system/blob/main/README_images/datalist.png)


### Recommendation

![recommendation](https://github.com/shadow-1310/book_recommendation_system/blob/main/README_images/recommend.png)


## Directory Structure

### Raw Data

- [Book details](https://github.com/shadow-1310/commodity-price-prediction/blob/main/car/notebooks/data/CAR%20DETAILS%20FROM%20CAR%20DEKHO.csv) :  book raw data containing the following fields
    - ISBN
    - Book-Title
    - Book-Author
    - Year-Of-Publication
    - Publisher
    - Image-URL-S
    - Image-URL-M
    - Image-URL-L

- [User details](https://github.com/shadow-1310/commodity-price-prediction/blob/main/laptop/notebooks/data/laptop_price.txt) :  contains raw data for Laptop Price Prediction app
    - User-ID
    - Location
    - Age

- [Ratings details](https://github.com/shadow-1310/commodity-price-prediction/blob/main/laptop/notebooks/data/laptop_price.txt) :  contains raw data for Laptop Price Prediction app
    - User-ID,
    - ISBN,
    - Book-Rating
### Notebooks for visualization

- [EDA Notebook](https://github.com/shadow-1310/commodity-price-prediction/blob/main/car/notebooks/CarDekho_predict_2.0.ipynb) :  Jupyter Notebook for Exploratory Data Analysis on the Raw data

- [Model Notebook](https://github.com/shadow-1310/commodity-price-prediction/blob/main/laptop/notebooks/price_predict_rTree.ipynb) :  Jupyter Notebook for model training and evaluation 


## Run Locally

Create a virtual environment (Mac or Linux)

```bash
  python3 -m venv project_venv
```

Activate the virtual environment

```bash
  source project_venv/bin/activate
```

Clone the git repository

```bash
  git clone https://github.com/shadow-1310/book_recommendation_system.git
```

Install the dependencies

```bash
  pip install -r requirements.txt
```

host the website locally

```bash
  python3 app.py 
```
## 🚀 About Me
An aspiring Data Scientist.
