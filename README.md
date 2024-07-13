# Credit-Card-Fraud-Detection
### Credit Card Fraud Detection Analysis

This notebook provides an analysis for detecting credit card fraud using various data science and machine learning techniques. Below is a summary of the steps and processes undertaken in the notebook:

#### Importing Libraries
The necessary libraries for data manipulation, visualization, and machine learning are imported:
- `pandas` and `numpy` for data manipulation
- `seaborn` and `matplotlib` for data visualization
- `sklearn` for machine learning models and evaluation

#### Data Loading and Initial Exploration
The credit card dataset is loaded from a CSV file, followed by an initial exploration:
- Displaying the dataset and checking its structure
- Verifying data types and checking for missing values

#### Data Analysis
The distribution of fraudulent and legitimate transactions is analyzed:
- The dataset is found to be highly imbalanced with a much larger number of legitimate transactions compared to fraudulent ones
- The distribution of transaction amounts for both legitimate and fraudulent transactions is examined

#### Data Visualization
Several visualizations are created to understand the data better:
- Pie chart to visualize the class distribution in percentage
- Heatmap to show the correlation between different features

#### Data Preprocessing
The preprocessing steps involve preparing the data for model training:
- Separating the dataset into legitimate and fraudulent transactions
- Analyzing the statistical properties of transaction amounts for both classes

#### Model Training
- Balancing the data for legitimate and fraudulent transactions
- Splitting the data into training and testing sets
- Training a Logistic Regression model on the training data
- Evaluating the model using accuracy, precision, recall, and classification report metrics

#### Conclusion
This notebook provides a detailed approach to data exploration, visualization, preprocessing, and model training to detect credit card fraud. The steps outlined ensure a thorough and methodical approach to handling and analyzing the credit card fraud detection dataset.

This analysis and the steps involved can serve as a valuable reference for similar machine learning projects, highlighting the importance of data preparation and proper evaluation metrics.

You can view and run this analysis using the provided Jupyter Notebook file in this repository.
