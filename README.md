# Customer Analysis E-commerce

## Goal
The goal of this project is to analyze customer data and help the company decide whether to focus efforts on their mobile app experience or their website.

## Overview
This dataset contains information about customers who buy clothes online. The store offers in-store style and clothing advice sessions. Customers have sessions with a personal stylist in the store, and then they can order either through a mobile app or website for the clothes they want.

## Data
The dataset is provided in a CSV file named `Ecommerce Customers.csv`.

### Columns
- `Avg. Session Length`: Average session length in minutes.
- `Time on App`: Time spent on the mobile app in minutes.
- `Time on Website`: Time spent on the website in minutes.
- `Length of Membership`: Number of years the customer has been a member.
- `Yearly Amount Spent`: Amount spent by the customer yearly.

## Exploratory Data Analysis (EDA)

### Visualizations
- Scatter plots, joint plots, and pair plots to understand relationships between variables.
- Linear regression plots to identify correlations.

### Conclusions
The analysis suggests that the most influential factor for clients is their length of membership, with the mobile app having a stronger impact than the website.

## Model Training

### Splitting the Data
The dataset is split into training and testing sets using the `train_test_split` function from scikit-learn.

### Linear Regression Model
A linear regression model is trained using the training data to predict the yearly amount spent by customers based on various features.

## Predictions and Evaluation

### Predictions
The model is used to make predictions on the test data.

### Evaluation Metrics
- Mean Absolute Error (MAE): [MAE value]
- Root Mean Squared Error (RMSE): [RMSE value]

## Residual Analysis
Residual analysis is performed to understand the model's performance.

## Interpretation and Conclusions
The length of membership and the mobile app are identified as significant factors. Recommendations are provided based on the analysis.

## Repository Structure
- `data/`: Folder containing the dataset.
- `notebooks/`: Jupyter notebooks used for data analysis.
- `scripts/`: Python scripts for data processing or model training.
- `README.md`: Documentation about the project.

## Getting Started
1. Clone the repository.
2. Install the required dependencies: `pip install -r requirements.txt`.
3. Run the Jupyter notebooks in the `notebooks/` folder.

## Dependencies
- pandas
- matplotlib
- seaborn
- scikit-learn
