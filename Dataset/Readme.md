## Overview

This project uses a used car dataset to predict the selling price of a vehicle using Machine Learning regression algorithms.

The dataset contains information related to vehicle specifications, ownership details, and selling price.

---

## Dataset Features

The dataset includes the following attributes:

- Car Name
- Year
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

The **Selling Price** is used as the target variable for prediction.

---

## Data Preprocessing

The following preprocessing steps were performed before model training:

- Removed unnecessary columns
- Converted categorical variables into numerical values
- Checked for missing values
- Split the dataset into training and testing sets
- Applied feature scaling where required

---

## Dataset Source

The dataset was obtained from **Kaggle** for educational and machine learning purposes.
 Dataset : https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset?

---

## Dataset Structure

```
Dataset/
│
└── car_data.csv
```

Place the dataset inside the **Dataset** folder before running the notebook.
