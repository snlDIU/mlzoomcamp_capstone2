
# **Machine Learning Capstone Project**
### **Boston House Pricing Prediction Project**

## **Introduction**

This notebook is part of the capstone project for the Machine Learning Zoomcamp course Cohort 2023. [Cohort 2023 GitHub](https://github.com/DataTalksClub/machine-learning-zoomcamp/tree/master/cohorts/2023) by [Alexey Grigorev](https://github.com/alexeygrigorev).

**The dataset used for this task is sourced from [Kaggle](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices).**

## **Problem Description**

The task at hand involves predicting housing prices in Boston based on various features associated with towns or suburbs. This regression problem aims to create a machine learning model capable of providing accurate predictions for house prices. The dataset used in this project is sourced from Kaggle and contains information about 506 unique Boston towns or suburbs.

### Dataset Details

The dataset comprises 506 entries, each representing a unique town or suburb in Boston. It consists of 13 features for each entry, with the target variable being the house price. These features encompass a wide range of aspects such as crime rate, residential land proportions, business acreage, proximity to the Charles River, nitric oxide concentration, average number of rooms, and more.

- **CRIM:** Per capita crime rate.
- **ZN:** Proportion of residential land zoned for lots over 25,000 sq.ft.
- **INDUS:** Proportion of non-retail business acres per town.
- **CHAS:** Charles River dummy variable (1 if tract bounds river; 0 otherwise).
- **NOX:** Nitric oxides concentration (parts per 10 million).
- **RM:** Average number of rooms per dwelling.
- **AGE:** Proportion of owner-occupied units built prior to 1940.
- **DIS:** Weighted distances to five Boston employment centers.
- **RAD:** Index of accessibility to radial highways.
- **TAX:** Full-value property-tax rate per $10,000.
- **PTRATIO:** Pupil-teacher ratio by town.
- **B:** \(1000(Bk - 0.63)^2\) where \(Bk\) is the proportion of blacks by town.
- **LSTAT:** Percentage of the lower status of the population.

### Objective

The primary goal is to build a robust machine learning model that, given the features mentioned above, accurately predicts the price of a house in Boston. The project involves data exploration, preprocessing, model building, evaluation, and selection.


### Exploring Machine Learning Models

The project explores various machine learning models for regression tasks. The following models were trained and evaluated:

- Linear Regression
- Random Forest 
- XGBRegressor
- Ridge

A set of metrics, including Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R-squared, Adjusted R-squared, Cross-Validated R-squared, and RMSE, were used for model evaluation.

## **Software and Tools Used**

To follow along and contribute to this project, you will need the following tools and accounts:

1. [GitHub Account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VSCode IDE](https://code.visualstudio.com/)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)
5. [Render Account](https://render.com)
6. [Jupyter](https://jupyter.org/)
7. [Docker](https://www.docker.com/)


## **Project Structure**

- **.github/workflows:** GitHub Actions workflows for continuous integration.
- **static:** Static files for the web application.
- **templates:** HTML templates for the web application.
- **app.py:** Python script for the web application.
- **dockerfile:** Configuration file for Docker.
- **housing.csv:** Dataset containing Boston housing information.

**Notebooks:**

- **ML_EDA.ipynb:** Jupyter notebook for EDA (Exploratory Data Analysis).
- **ML_Model_selection.ipynb:** Jupyter notebook for model selection and evaluation.


**Model Artifacts:**

- **XGBR.pkl:** Pickle file containing the trained XGBoost regression model.
- **scaling.pkl:** Pickle file containing the scaling information.

### Dockerization

Docker is used to containerize the application, ensuring seamless deployment across different environments. The Dockerfile in the project specifies the configuration for creating a Docker container, including necessary dependencies and settings.

## **Deployment Links**

I have experimented with Heroku and Render deployment to learn. Here are both deployment links to share:

- [Heroku Deployment](https://predicthouseprice-ef7c71e13c16.herokuapp.com/) - [https://predicthouseprice-ef7c71e13c16.herokuapp.com/](https://predicthouseprice-ef7c71e13c16.herokuapp.com/)
- [Render Deployment](https://predict-house-price-zxbr.onrender.com/) - [https://predict-house-price-zxbr.onrender.com/](https://predict-house-price-zxbr.onrender.com/)

The Render website may take time to load.

## **Screenshot**

![Deployment Screenshot](https://github.com/snlDIU/mlzoomcamp_capstone2/blob/main/DeploymentScreenshot.png)

## **How to Run the Application**

**Setting Up the Environment**

To set up the environment, follow these steps:

```bash
# Create a new environment
conda create -p venv python==3.7 -y
conda activate venv/

# Install required packages
pip install -r requirements.txt
```

Execute the following commands:

```bash
python app.py
```

Visit [http://localhost:5000](http://localhost:5000) in your web browser to interact with the application locally.

Feel free to explore the Jupyter notebooks for an understanding of the project's data exploration and model selection processes.

## **Conclusion**

As a newcomer to machine learning, I acknowledge that this project is a starting point. I understand that there is more to explore and learn in the field of ML. I look forward to updating and expanding on this project in the future.

Thank you for reviewing my work.

*Another Machine Learning Enthusiast*



