# EDA & Customer Clustering: Overview

In this project, im download data transaction from [Kaggle](https://www.kaggle.com/zusmani/pakistans-largest-ecommerce-dataset) and performing EDA and also doing clustering using Elbow Method & Silhoulette Method.

## Codes & Resources Used
- Editor Used : VS Code
- Python version : 3.8.8
- Package used : numpy, pandas, plotly, sklearn

## About the dataset
this dataset i get from [Kaggle](https://www.kaggle.com/zusmani/pakistans-largest-ecommerce-dataset) which is transactional dataset.

## Data Cleaning
The data is preprocessed and transform as required to avoid data redudant and skew the result.
data cleaning step : 
- change format data
- drop unused columns
- drop some strange data (amount less than 0)
- drop null data
- rename some columns
- simplify status

## cluster algorithm used : 
- Elbow method <br />
![elbow-method](https://user-images.githubusercontent.com/41662335/144379977-bf4e9bcd-4a9e-4c47-aad4-c54c03a4f9e5.png)

- Silhoulette method <br />
![4-center](https://user-images.githubusercontent.com/41662335/144380075-bb7472ba-88cb-49b3-9b0e-2b8d922d8aeb.png)
![5-center](https://user-images.githubusercontent.com/41662335/144380160-5b12b32f-73c8-48f0-b7c4-471215963703.png)
