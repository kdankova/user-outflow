# Customer Churn Prediction for a Telecommunications Company

This project focuses on predicting customer churn for a telecommunications company. Customer churn is a critical issue in the telecom industry, and developing effective algorithms to predict churn allows companies to take timely measures to retain customers by offering various bonuses and offers.

## Project Structure

The project is structured as follows:

1. **Data Loading and Preprocessing:** The train dataset is loaded and preprocessed. This includes checking for missing values and understanding the structure of the dataset.

2. **Exploratory Data Analysis (EDA):** Key features of the dataset are explored, including numerical and categorical features. The analysis helps in understanding the distribution and relationships within the data.

3. **Model Building:** Several machine learning models are considered, with a focus on evaluating their performance using the ROC-AUC metric, which is well-suited for imbalanced datasets like churn prediction.

4. **Model Training and Evaluation:** The selected model is trained on the processed data, and its performance is evaluated using cross-validation and the ROC-AUC metric.

## Data Overview

The dataset used contains the following columns:

- **ClientPeriod:** Duration of client service usage in months.
- **MonthlySpending:** Monthly spending amount by the client.
- **TotalSpent:** Total amount spent by the client over the entire period.
- **Sex:** Gender of the client (`Male` or `Female`).
- **IsSeniorCitizen:** Whether the client is a senior citizen (`1` — yes, `0` — no).
- **HasPartner:** Whether the client has a spouse or partner (`Yes` or `No`).
- **HasChild:** Whether the client has children (`Yes` or `No`).
- **HasPhoneService:** Whether the client has phone service (`Yes` or `No`).
- **HasMultiplePhoneNumbers:** Whether the client has multiple phone numbers (`Yes`, `No`, `No phone service`).
- **HasInternetService:** Whether the client has internet service (`DSL`, `Fiber optic`, `No`).
- **HasOnlineSecurityService:** Whether the client has an online security service (`Yes`, `No`, `No internet service`).
- **HasOnlineBackup:** Whether the client has an online backup service (`Yes`, `No`, `No internet service`).
- **HasDeviceProtection:** Whether the client has device protection service (`Yes`, `No`, `No internet service`).
- **HasTechSupportAccess:** Whether the client has access to technical support (`Yes`, `No`, `No internet service`).
- **HasOnlineTV:** Whether the client has online TV service (`Yes`, `No`, `No internet service`).
- **HasMovieSubscription:** Whether the client has a movie subscription service (`Yes`, `No`, `No internet service`).
- **HasContractPhone:** The type of contract the client has (`Month-to-month`, `One year`, `Two year`).
- **IsBillingPaperless:** Whether the client receives paperless billing (`Yes` or `No`).
- **PaymentMethod:** The payment method used by the client (`Electronic check`, `Mailed check`, `Bank transfer (automatic)`, `Credit card (automatic)`).

## Running the Model

To run the model, simply execute the Python notebook. The notebook will train the model and, based on the data, provide predictions that can be saved for further analysis or submission.

## Dependencies

This project uses the following libraries:

- scikit-learn
- Pandas
- NumPy
- Matplotlib

## Setup

This application requires Python 3.6 or higher. All required libraries can be installed using the following command:

```shell
pip install -r requirements.txt
