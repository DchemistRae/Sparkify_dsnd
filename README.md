# Sparkify User Churn Analysis and Prediction

This project is part of the Udacity Data Scientist Nanodegree program. The goal of this project is to analyze user data from the fictional music streaming service Sparkify, and build a model to predict which users are likely to cancel their subscription.

A dataset containing users activity data was analysed to predict if a customer will churn at somepoint in time or stay with the service. This is important to identify users that might leave and offer them coupons or special promotions to get them to continue using sparkify music streaming service.This project is about demonstrating knowledge of spark scalable data manipulation and machine learning techniques

## Packages used
This project requires Python 3.x and the following Python libraries:

- Pyspark
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Blog
Description of this project and results is available on medium using this [link](url_here). This blog provides more indepth information relating to the project technicalities and also explains more about churn and why it is an important metric in business.

## Data Description

The dataset used in this project is the Sparkify event log dataset, which contains user data for a fictional music streaming service. The dataset includes information such as user demographics, session data, and song play data. See the schema below.

                |-- artist: string (nullable = true)
                |-- auth: string (nullable = true)
                |-- firstName: string (nullable = true)
                |-- gender: string (nullable = true)
                |-- itemInSession: long (nullable = true)
                |-- lastName: string (nullable = true)
                |-- length: double (nullable = true)
                |-- level: string (nullable = true)
                |-- location: string (nullable = true)
                |-- method: string (nullable = true)
                |-- page: string (nullable = true)
                |-- registration: long (nullable = true)
                |-- sessionId: long (nullable = true)
                |-- song: string (nullable = true)
                |-- status: long (nullable = true)
                |-- ts: long (nullable = true)
                |-- userAgent: string (nullable = true)
                |-- userId: string (nullable = true)
                
## Files

- `Sparkify.ipynb`: This Jupyter notebook contains the code for the data analysis and modeling process. It includes exploratory data analysis, data preprocessing, feature engineering, and model training and evaluation.
- `README.md`: This file provides an overview of the project

## Usage

To run the code, simply open the `Sparkify.ipynb` notebook and follow the instructions within. The notebook is designed to be run sequentially, with each section building on the previous sections.

## Results

The final model achieved an F1 score of 0.88 on the validation set, indicating that it is able to accurately predict which users are at risk of canceling their subscription. This information can be used by Sparkify to proactively target these users with retention campaigns, and improve customer retention overall.

## Acknowledgements

- The Sparkify dataset was provided by Udacity as part of the Data Scientist Nanodegree program.
- This project builds upon knowledge gained from Udacity Data Scientist Nanodegree and the Spark course offered Udacity
