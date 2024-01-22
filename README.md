### Boston House Pricing Prediction Project

**Machine Learning Capstone Project**

*Introduction*

This notebook is part of the capstone project for the Machine Learning Zoomcamp course Cohort 2023. [Cohort 2023 GitHub](https://github.com/DataTalksClub/machine-learning-zoomcamp/tree/master/cohorts/2023)

Welcome to the Boston House Pricing Prediction project! This repository contains code and resources for predicting housing prices in Boston using machine learning. Whether you're a data enthusiast or a developer, this project offers valuable insights into the realm of predictive modeling and real estate analytics.

**The dataset used for this task is sourced from [Kaggle](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices).**

#### Objective

The primary goal of this project is to build a robust machine learning model capable of accurately predicting housing prices based on various features associated with towns or suburbs in Boston. The project involves data exploration, preprocessing, model building, evaluation, and selection.

#### Software and Tools Requirements

1. [GitHub Account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VSCode IDE](https://code.visualstudio.com/)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)
5. [Render Account](https://render.com)
6. [Jupyter](https://jupyter.org/)
7. [Docker](https://www.docker.com/)

#### Setting Up the Environment

To set up the environment, follow these steps:

```bash
# Create a new environment
conda create -p venv python==3.7 -y
conda activate venv/

# Install required packages
pip install -r requirements.txt
```

#### Project Structure

- **.github/workflows:** GitHub Actions workflows for continuous integration.
- **static:** Static files for the web application.
- **templates:** HTML templates for the web application.
- **app.py:** Python script for the web application.
- **dockerfile:** Configuration file for Docker.
- **housing.csv:** Dataset containing Boston housing information.

**Notebooks:**

- **ML_EDA.ipynb:** Jupyter notebook for Exploratory Data Analysis.
- **ML_Model_selection.ipynb:** Jupyter notebook for model selection and evaluation.

**Model Artifacts:**

- **XGBR.pkl:** Pickle file containing the trained XGBoost regression model.
- **scaling.pkl:** Pickle file containing the scaling information.

#### Dockerization

Docker is used to containerize the application, ensuring seamless deployment across different environments. The Dockerfile in the project specifies the configuration for creating a Docker container, including necessary dependencies and settings.

#### Deployment Links

- [Heroku Deployment](https://predict-house-price.herokuapp.com) - https://predict-house-price.herokuapp.com
- [Render Deployment](https://predict-house-price-zxbr.onrender.com) - https://predict-house-price.herokuapp.com

**Screenshot**

![Deployment Screenshot](https://github.com/snlDIU/mlzoomcamp_capstone2/blob/main/DeploymentScreenshot.png)

#### How to Run the Application

Execute the following commands:

```bash
python app.py
```

Visit [http://localhost:5000](http://localhost:5000) in your web browser to interact with the application locally.

Feel free to explore the Jupyter notebooks for a deeper understanding of the project's data exploration and model selection processes.

#### Conclusion

As a newcomer to machine learning, I acknowledge that this project is a starting point. I understand that there is more to explore and learn in the field of ML. I look forward to updating and expanding on this project in the future.

Thank you for reviewing my work.

*Another Machine Learning Enthusiast*