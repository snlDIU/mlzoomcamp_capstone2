
# **Machine Learning Capstone Project**
### **Boston House Pricing Prediction Project**

## **Introduction**

Welcome to the Boston House Pricing Prediction project! This repository is a part of the [Machine Learning Zoomcamp course Cohort 2023](https://github.com/DataTalksClub/machine-learning-zoomcamp/tree/master/cohorts/2023) by [Alexey Grigorev](https://github.com/alexeygrigorev), and it focuses on predicting housing prices in Boston using machine learning.

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices).

## **Objective**

The primary goal of this project is to build a machine learning model capable of predicting housing prices based on various features associated with towns or suburbs in Boston. The project involves data exploration, preprocessing, model building, evaluation, and selection.

## **Exploring Machine Learning Models**

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

- **ML_EDA.ipynb:** Jupyter notebook for Exploratory Data Analysis.
- **ML_Model_selection.ipynb:** Jupyter notebook for model selection and evaluation.
- **Additional_Models.ipynb:** Jupyter notebook exploring additional machine learning models for predicting math scores.

**Model Artifacts:**

- **XGBR.pkl:** Pickle file containing the trained XGBoost regression model.
- **scaling.pkl:** Pickle file containing the scaling information.

### **Dockerization**

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