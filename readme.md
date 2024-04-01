# Weather Forecasting Project

## Overview
This project aims to forecast weather patterns in New York City using historical data collected from [Wunderground](https://www.wunderground.com/). The project utilizes the Selenium framework and a Chrome browser for web scraping. Data analysis and modeling are conducted to understand weather trends and make predictions.

## Contents
1. [Introduction](#introduction)
2. [Setup](#setup)
3. [Data Understanding](#data-understanding)
4. [Exploratory Data Analysis (EDA)](#eda)
5. [Data Preparation](#data-preparation)
6. [Modeling](#modeling)
7. [Evaluation](#evaluation)
8. [License](#license)

## Introduction <a name="introduction"></a>
Weather forecasting is a challenging task, and this project aims to predict weather patterns in New York City. Historical weather data from 2009 to 2023 collected from Wunderground is used for analysis and modeling. Various weather features are considered, and the Vector Autoregression (VAR) algorithm is employed for modeling.

## Setup <a name="setup"></a>
To set up the project environment, install the required libraries listed in the `requirements.txt` file. Use the following command:
```bash
pip install -r requirements.txt
```

## Data Understanding <a name="data-understanding"></a>
The historical weather data is collected from Wunderground for New York City's LaGuardia Airport station. The dataset contains daily observations of 13 important weather features from 2009 to 2023, totaling 5452 rows.

## Exploratory Data Analysis (EDA) <a name="eda"></a>
EDA is performed to understand the distribution and relationships between weather features. Various visualizations using Plotly Express and Plotly Graph Objects are created to analyze weather patterns over time.

## Data Preparation <a name="data-preparation"></a>
Data preprocessing techniques such as scaling and encoding are applied to prepare the dataset for modeling. Missing values are handled, and features are transformed as necessary.

## Modeling <a name="modeling"></a>
The VAR algorithm is utilized for modeling weather patterns. The dataset is split into training and testing sets, and the model is trained using the training data. Evaluation metrics such as RMSE are used to assess the model's performance.

## Evaluation <a name="evaluation"></a>
The trained model is evaluated on the testing dataset to assess its accuracy in forecasting weather patterns. Results are analyzed to determine the model's effectiveness in predicting future weather conditions.

## License <a name="license"></a>
This project is licensed under the [GNU General Public License (GPL)](LICENSE).


Many thanks to [Epsilon AI](https://github.com/EPSILON-AI)
