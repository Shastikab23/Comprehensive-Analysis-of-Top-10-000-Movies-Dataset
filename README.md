README for Comprehensive Analysis of Top 10,000 Movies Dataset

Project Overview

This project explores the "Top 10,000 Movies" dataset, analyzing various attributes such as genres, popularity, revenue, and ratings. The goal is to uncover insights about trends in the movie industry, predict key outcomes using machine learning models, and provide actionable recommendations for stakeholders.

Files and Structure

Report.pdf: Comprehensive analysis, visualizations, and machine learning results.

Dataset.csv: The raw dataset used for analysis.

Scripts/: Python scripts for data cleaning, exploratory data analysis, and modeling.

Plots/: Directory containing all generated visualizations.

Key Sections of the Report

1. Data Loading and Initial Exploration

Dataset Overview:

Attributes include title, release date, genres, revenue, popularity, and more.

Initial findings highlight missing values and the need for column formatting.

2. Data Cleaning

Process:

Removed extra spaces in column names.

Imputed or dropped rows with missing values.

Standardized date formatting.

Converted revenue to numeric format.

3. Exploratory Data Analysis (EDA)

Genre Distribution: Action, Adventure, and Drama are the most popular genres.

Revenue Insights: Blockbusters dominate revenue, with a significant skew toward top-performing movies.

Popularity Trends: Modern marketing strategies increase recent movies’ popularity.

Vote Patterns: Movies with more votes exhibit balanced ratings.

4. Key Analysis and Visualizations

Revenue vs. Popularity: A scatterplot reveals that while most popular movies generate high revenue, some outliers exist.

Genre and Revenue: Action and Adventure are consistently the highest revenue-generating genres.

Vote Count vs. Vote Average: Demonstrates that larger vote counts yield more stable ratings.

5. Predictive Modeling

Models Implemented:

Linear Regression: Predicts revenue based on features like popularity, runtime, and vote count.

Random Forest: Predicts movie popularity with higher accuracy due to its ability to capture non-linear relationships.

Logistic Regression: Classifies movies as high-revenue or low-revenue based on specific thresholds.

Key Results:

Random Forest outperformed other models for popularity prediction.

Logistic Regression achieved reasonable accuracy for revenue classification.

Predicting revenue remains challenging due to external factors not captured in the dataset.

6. Recommendations

Focus on franchise-building in Action and Adventure genres.

Leverage social media and global appeal for marketing new releases.

Encourage audience engagement to boost vote counts and ratings.

Tools and Technologies Used

Python: Data cleaning, EDA, and modeling.

Libraries: Pandas, Matplotlib, Seaborn, Scikit-learn.

Jupyter Notebooks: Interactive development and visualization.

How to Run the Project

Clone the repository.

Install required Python libraries listed in requirements.txt.

Run data_cleaning.py to preprocess the dataset.

Execute eda.py to generate visualizations.

Use modeling.py to train and evaluate predictive models.

Future Work

Incorporate additional datasets to enrich insights.

Explore advanced modeling techniques such as Neural Networks.

Investigate marketing and distribution factors influencing movie revenue.
