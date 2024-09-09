# Reservation Deposit Prediction for a Hotel Chain

## Project Overview

This project aims to predict hotel reservation cancellations using customer and booking data. The main objective is to implement a deposit system to reduce cancellations and increase hotel profits.

## Project Goals
1. Develop a machine learning model to predict reservation cancellations.
2. Analyze the impact of deposits on customer behavior and hotel profitability.
3. Calculate the potential financial benefit of implementing a deposit system.

## Dataset Overview
The dataset includes the following features:
- Lead time (days before check-in).
- Number of adults, children, and babies.
- History of cancellations.
- Special requests made by customers.
- Booking channel and customer type.
- Parking space requests.
- Total booking cost.

The dataset was split into training and test sets.

## Project Steps

1. **Data Preprocessing**:
   - Removal of duplicates.
   - Handling missing values and outliers.
   - Encoding categorical features.
   
2. **Model Training**:
   - Two models were trained and tested: Logistic Regression and Random Forest.
   - Model performance was evaluated using metrics such as Recall, Precision, and F1-Score.
   - The Random Forest model performed better on the test set.

3. **Analysis and Prediction**:
   - Financial losses from cancellations were calculated.
   - The impact of implementing a deposit system was modeled.
   - Exploratory Data Analysis (EDA) was conducted to identify common patterns among customers who cancel reservations.

## Key Results
- The best-performing model, Random Forest, achieved a Recall of 0.79 and Precision of 0.89 on the test data.
- The potential profit gain from implementing the deposit system was estimated to be over 13 million RUB.

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Git and GitHub for version control

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Zholly18/deposit-for-hotel-chain.git

2. Install required libraries
 pip install -r requirements.txt

3. Run the Jupyter Notebook to explore and execute the project code.
